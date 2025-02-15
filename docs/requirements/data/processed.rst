Processed Data
--------------

Processed Data is produced when **raw data** is **transformed** through
**analytic** or **deterministic** tools.

.. ifnotslides::

   -   Unless carefully produced, processed Data can contribute to extremely **high storage** volume needs.

   -   **Balancing** the **computational effort** needed to produce the processed data against **storage volumes** needed to store it is critical to **efficiency**.

   -   **Tuning** the **analytic** and **deterministic** tools to limit the production of processed data to only that needed to serve the decision making end can minimize both processing and storage needs.

   -   In some cases, **high computational** effort and **high processed storage volumes** cannot be avoided, in which case, processed may be **condensed** through further analytic processing to reduce the volume of storage needed while **maintaining** the **intrinsic value** of the processing.

   -   **Caching** should be used to reduce the **volume** for **storage** over **time**.

.. ifslides::

   -   High Storage Volume
   
   -   Balance Computation with Storage
   
   -   Tune Tools to Access Minimal Data
   
   -   Condense/Synthesize Processed Data
   
   -   Caching over time