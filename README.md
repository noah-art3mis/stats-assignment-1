# LIS MASc Everything Counts Assignment 1

CCUS

The IEA produced this dataset as part of efforts to track advances in carbon capture, utilisation, and storage (CCUS). It covers all CO2 capture, transport, storage, and utilisation projects worldwide that have been commissioned since the 1970s, with an announced capacity of more than 100 000 t per year (or 1000 t per year for direct air capture facilities). It includes projects with a clear emissions reduction scope, and excludes CO2 capture for utilisation pathways which bring low climate benefits (e.g. food and beverages) or which are part of the conventional industrial process (e.g. internal use for urea production), as well as use of naturally occurring CO2 for enhanced oil recovery (EOR). When the capacity is unknown, only projects with a clear commercial scope are included. If an industrial cluster has been announced, only identified CO2 capture projects within this cluster are included (i.e. it does not include the full potential capture capacity of industrial clusters for which capture sources are not specified). Capture projects for CO2 use are included as long as the source of the CO2 (i.e. capture facility) has been clearly identified. Projects are categorised by type (capture, full chain, transport, storage, CCU), sector of point source (fuel transformation, power and heat, industry, direct air capture, etc.), and fate of CO2 (dedicated storage, EOR, utilisation, unknown/unspecified). Detailed definitions for each column are available in the Definitions tab. Project announcements as of February 2024 are included. Data Data collection and processing by the IEA. All public references are available by project. Notes on how to aggregate the data are available in Aggregation notes. For any feedback or questions please contact ccsinfo@iea.org.

## Feature description

- **Country**: 
  - Country of project location.

- **Project partners**: 
  - Includes project developers, technology providers (''tech''), and contractors, including for feasibility, front-end engineering and design (FEED), equipment procurement and construction (EPC), etc. when applicable/known.

- **Announcement**: 
    -   Year of project announcement.
- **FID**: 
    - Actual or planned year of final investment decision (FID).
- **Operation**: 
    - Actual or planned year of project commissioning.
- **Suspension/decommissioning**: 
    - Actual year of suspension/decommissioning.

- **Project Phase**: 
  - If projects have defined announced phases or plan to develop capacity in a stepwise manner, this column is used. Phasing starts from 1. Announced capacity across phases is additional, not cumulative.

- **Announced capacity (Mt CO2 per year)**: 
  - Announced or actual capture, transport and/or storage CO2 capacity, in Mt CO2 per year. When capture capacity is announced as a range, or several values are available, announced capacity is entered as a range.

- **Estimated capacity by IEA (Mt CO2 per year)**: 
  - Estimated capture capacity based on other plant details (e.g. fuel production capacity) or potential deployment plans. See conversion factors for further assumptions.

- **Part of CCUS hub**: 
  - If a capture, transport or storage project is developed as part of a CCUS hub (capture facilities connected to a network of CO2 storage sites by shared transport infrastructure), the name of the corresponding hub is indicated.
  

- **Project Status**: 
  - **Planned**: Project at concept, feasibility or engineering study (FEED) stage. Concept projects include announcements with little to no further information available (e.g. capture technology, site, stakeholders, budget, timeline).
  - **Under construction**: A final investment decision (FID) has been announced and construction is ongoing or imminent.
  - **Operational**: Project has been commissioned and is running.
  - **Suspended**: Project operation is suspended for more than six months.
  - **Decommissioned**: Project operation is permanently stopped.

- **Project Type**: 
  - **Full chain**: Projects where CO2 is transported from one capture facility to one injection site, typically involving a single operator.
  - **Capture**: Capture-only project (project does not include any transport and storage development but can be developed as part of a CCUS hub).
  - **Transport**: CO2 transport-only project, which may include CO2 shipping, pipelines, terminals with liquefaction stations/buffer storage, etc.
  - **Storage**: CO2 storage-only project (no mention of connecting infrastructure), including both dedicated storage and CO2 enhanced oil recovery (EOR).
  - **T&S**: CO2 transport and storage project which includes both transport and storage development.
  - **CCU**: A project that captures CO2 for use (excluding internal use such as urea production) with significant climate benefits and a clearly identified source for the captured CO2.

- **Sector**: 
  - **Power and heat**: Capture, full chain, and CCU projects which capture CO2 from power and heat facilities (includes waste-to-energy plants).
  - **Natural gas processing/LNG**: Capture, full chain, and CCU projects which capture CO2 from natural gas processing and liquefied natural gas (LNG) trains.
  - **Biofuels**: Capture, full chain, and CCU projects which capture CO2 from bioethanol, biodiesel, and biogas facilities.
  - **Hydrogen/ammonia**: Capture, full chain, and CCU projects which capture CO2 from off-site hydrogen and ammonia production. When CO2 is captured on a hydrogen production plant for on-site use (e.g. iron and steel, refinery, fertilizer), the sector is tagged as the main application.
  - **Other fuel transformation**: Capture, full chain, and CCU projects which capture CO2 from other fuel transformation facilities including refineries, coal-to-gas, coal-to-liquids, and gas-to-liquids plants.
  - **Cement**: Capture, full chain, and CCU projects which capture CO2 from cement and lime facilities.
  - **Iron and steel**: Capture, full chain, and CCU projects which capture CO2 from iron and steel plants.
  - **Chemicals**: Capture, full chain, and CCU projects which capture CO2 from chemical and fertiliser plants.
  - **Other industry**: Capture, full chain, and CCU projects which capture CO2 from other industrial facilities including aluminium smelters, pulp and paper mills, etc.
  - **DAC**: Direct air capture plant.
  - **Transport**: CO2 transport project.
  - **Storage**: CO2 storage project.
  - **T&S**: CO2 transport and storage project.

- **Fate of Carbon**: 
  - **Dedicated storage**: CO2 is injected deep underground and stored permanently in a dedicated storage site.
  - **EOR**: CO2 is used for enhanced oil recovery.
  - **Use**: CO2 is used in a product with significant climate benefits. Internal use (e.g. CO2 capture and use in urea production) is excluded.
  - **Unknown/unspecified**: Fate of carbon has not been communicated.

## Assessment [criteria](https://cortex.lis.ac.uk/courses/311/pages/assessment-brief)

Describe datasets using relevant statistical measures

-   [] Demonstrate familiarity and technical proficiency in identifying and visualising the relevant measures.
-   [] Being comprehensive in identifying all relevant measures.
-   [] Expertise in using python data science and visualisation libraries.
-   [] Refine your use of core course concepts so that they are applied in ways that are notably insightful or novel.
-   [] Identify non-obvious features of dataset.
-   [] Engage in processes of data cleaning on otherwise hard-to-work-with datasets.

## Refs

-   [x] https://matplotlib.org/stable/gallery/style_sheets/style_sheets_reference.html
-   [x] https://realpython.com/pandas-plot-python/
-   [x] https://elitedatascience.com/python-seaborn-tutorial
-   [x] https://medium.com/analytics-vidhya/how-to-make-better-looking-charts-in-python-81058bd37ac3
-   [x] https://frankcorso.dev/seaborn.html
-   [x] https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html
-   [] https://tryolabs.com/blog/2017/03/16/pandas-seaborn-a-guide-to-handle-visualize-data-elegantly
-   [] https://seaborn.pydata.org/tutorial/introduction.html
-   [] https://www.futurelearn.com/info/courses/data-visualisation-with-python-seaborn-and-scatter-plots/0/steps/314467
