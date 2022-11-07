# Data Dictionary
[![As-Is](https://img.shields.io/badge/Support%20Level-As--Is-e8762c.svg)](https://www.tableau.com/support-levels-it-and-developer-tools)

Tableau data dictionary provides information about the information stored in tables and views in the "workgroup" PostgreSQL database of the Tableau Server repository.

# What is data dictionary used for?

This workgroup database provides persistent storage for Tableau Server and is primarily intended to support Tableau Server. This information can be used to build custom views and custom reporting that can provide additional monitoring data, and build your own analysis of server activity.

# How to read the information provided here:

The purpose of most tables is described, along with the type and purpose of columns in the tables. Foreign key relations are noted in orange rows with links that take you from the table containing the foreign key to the primary key table. This is not an exhaustive description of all tables and fields in the database, but is provided here for those customers who want to query it for information about their Tableau Server usage. This information is provided with a caution that because the purpose of these tables and views is primarily to support Tableau Server, their structure and contents may change without warning and as a result, any custom views built from them may break.

Each subdirectory contains files related that specific release.

# Who can help answer questions about the data dictionary?

For more information about the Data Dictionary and how it is being used by other customers, see the [Tableau Community](https://community.tableau.com/s/global-search/%40uri#q=data%20dictionary&t=Community).

# What rights are granted for the data dictionary?

Tableau maintains and updates the data dictionary. You may use, copy, and/or distribute copies of the data dictionary, free of charge, provided that you should always include this readme file with the data dictionary.

