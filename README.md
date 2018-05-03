# SSUP

**SSUP** is a method for entity-page discovery. Given an entity-page of a website, **SSUP** finds the set of entity-pages in the website. For example, given the page describing Fernando Alonso in the Formula 1 official website, **SSUP** finds the pages that describe the drivers in this website. 

# Concepts

- **entity-page**: a page that describes an entity of a specific type. For example, the page that describes Fernando Alonso (driver) in the Formula 1 official website. 

- **entity-page discovery**: the task of discovery entity-pages in the websites.

- **SSUP**: a method we proposed for entity-page discovery.

# Demo version

Please send an e-mail to edimar.manica at ibiruba.ifrs.edu.br asking a demo version of **SSUP** and providing the following information: name, affiliation and goal.

# Datasets

The evaluation was carried out over 38 real-world websites. For each website *sx*: (i) the set of pages in the *sx* website were collected; (ii) an entity type *ty* (e.g. driver in a website about a car racing championship) was defined; and (iii) the ground truth (the set of entity-pages of the *ty* type that are in the *sx* website) was obtained through hand-crafted rules. These websites were grouped into three datasets:

- **Multiple types** - comprises 10 websites with entity-pages of different types. Links: [Web pages](https://mega.nz/#!BQ8QgShZ!TXyvx9Xcph5MlyCPFnhAe5u1jSwAMXTEn2O7zOzZbZg) | [Ground-truth](ground-truth/dataset_m);

- **Drivers** - contains 10 websites with entity-pages about drivers. Links: [Web pages](https://mega.nz/#!hNcCiaxL!RYE-BU03rP1VD3i8Z0ksi0Zvl1qDNkRKYFId_6vVEj4) | [Ground-truth](ground-truth/dataset_d1); and

- **Council members** - has 18 websites with entity-pages about council members. The official websites of the city council of the 26 Brazilian State capitals were analyzed. We excluded four websites because they did not have an entity-page for each council member, three websites because all the entity-pages were internal frames of a single page, and one website because it did not allow crawling its pages. Links: [Web pages](https://mega.nz/#!dAkDRSYY!y12Vvd_M-_kXwRPMaqH5bWAT6wWZ1edS6M2Y0dOGWjk) | [Ground-truth](ground-truth/dataset_c).

# References
