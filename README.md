In this project, our team was tasked with creating and managing the Central Donation Repository within an Oracle database instance. We implemented a robust system to handle donations, donor information, and volunteer data. To ensure data accuracy and integrity, we established processes for refreshing the address table from an authoritative SQL Server database and loading donation data from CSV files. These processes were designed to handle any number of input files and ensure that only valid entries were inserted into the repository.
![firstImage](https://github.com/aniketsha/DatabaseProject/assets/90695737/defa9355-f258-4479-8a17-9d115e8e66b5)
we developed views to provide management and stakeholders with valuable insights into donation statistics, collected by date, location hierarchy, and volunteer involvement. These views were carefully crafted to match the desired format specified by management. Additionally, we designed a star schema for the donations data mart, enabling efficient analysis of donation patterns and trends. This schema included dimensions for date, address, and volunteer, facilitating comprehensive reporting.
![2ndImage](https://github.com/aniketsha/DatabaseProject/assets/90695737/ce323f1a-f958-456a-85e4-0d5bc6d7916a)

To ensure data security, we implemented user roles and permissions. ETLUser was granted access to read from the Central Donation Repository and write to the DataMart tables, while Dashboard was given read access to the views. Through meticulous configuration and testing, we demonstrated that our security measures were effectively implemented and aligned with project requirements. Overall, our project showcases our team’s expertise in database management, data integration, and security implementation, making it a valuable addition to our portfolio.
