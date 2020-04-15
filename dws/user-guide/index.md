# User Guide

-   [Introduction](introduction.md)
    -   [DWS Overview](dws-overview.md)
    -   [Functions](functions.md)
    -   [Application Scenarios](application-scenarios.md)
    -   [Related Services](related-services.md)
    -   [Basic Concepts](basic-concepts.md)
        -   [DWS Management Concepts ](dws-management-concepts.md)
        -   [DWS Database Concepts](dws-database-concepts.md)


-   [Accessing and Using DWS](accessing-and-using-dws.md)
    -   [DWS Access and Use](dws-access-and-use.md)
    -   [Requirements and Limitations](requirements-and-limitations.md)
    -   [User Permissions](user-permissions.md)

-   [Getting Started](getting-started.md)
    -   [Step 1: Starting Preparations](step-1-starting-preparations.md)
    -   [Step 2: Creating a Cluster](step-2-creating-a-cluster.md)
    -   [Step 3: Connecting to a Cluster](step-3-connecting-to-a-cluster.md)
    -   [Step 4: Creating Access Keys \(AK and SK\)](step-4-creating-access-keys-(ak-and-sk).md)
    -   [Step 5: Importing Sample Data to a Data Warehouse Cluster](step-5-importing-sample-data-to-a-data-warehouse-cluster.md)
    -   [Step 6: Testing and Analyzing Data](step-6-testing-and-analyzing-data.md)
    -   [Step 7: Viewing Other Documents and Clearing Resources](step-7-viewing-other-documents-and-clearing-resources.md)

-   [Managing Clusters](managing-clusters.md)
    -   [Accessing the DWS Management Console](accessing-the-dws-management-console.md)
    -   [Creating a Cluster](creating-a-cluster.md)
    -   [Viewing the Cluster List](viewing-the-cluster-list.md)
    -   [Viewing Basic Cluster Information](viewing-basic-cluster-information.md)
    -   [Managing Access Domain Names](managing-access-domain-names.md)
    -   [Managing Clusters That Fail to Be Created](managing-clusters-that-fail-to-be-created.md)
    -   [Configuring Cluster Security Settings](configuring-cluster-security-settings.md)
        -   [Separating Rights of Roles](separating-rights-of-roles.md)

    -   [Resetting the Password of the Cluster Administrator](resetting-the-password-of-the-cluster-administrator.md)
    -   [Managing Tags](managing-tags.md)
        -   [Tagging Overview](tagging-overview.md)
        -   [Tag Management](tag-management.md)

    -   [Scaling Out a Cluster](scaling-out-a-cluster.md)
    -   [Restarting a Cluster](restarting-a-cluster.md)
    -   [Upgrading a Cluster](upgrading-a-cluster.md)
    -   [Deleting a Cluster](deleting-a-cluster.md)

-   [Connecting to a Cluster](connecting-to-a-cluster.md)
    -   [Methods of Connecting to a Cluster](methods-of-connecting-to-a-cluster.md)
    -   [Obtaining the Cluster Connection Address](obtaining-the-cluster-connection-address.md)
    -   [Configuring SSL Connection](configuring-ssl-connection.md)
    -   [Downloading the SSL Certificate File](downloading-the-ssl-certificate-file.md)
    -   [Using the gsql CLI Client to Connect to a Cluster](using-the-gsql-cli-client-to-connect-to-a-cluster.md)
        -   [Downloading the Client](downloading-the-client.md)
        -   [Preparing an ECS as the gsql Client Host](preparing-an-ecs-as-the-gsql-client-host.md)
        -   [Using the gsql Client to Connect to a Cluster](using-the-gsql-client-to-connect-to-a-cluster.md)
        -   [Establishing Secure TCP/IP Connections in SSL Mode](establishing-secure-tcp-ip-connections-in-ssl-mode.md)

    -   [Using pgAdmin to Connect to a Cluster](using-pgadmin-to-connect-to-a-cluster.md)
    -   [Using the Data Studio GUI Client to Connect to a Cluster](using-the-data-studio-gui-client-to-connect-to-a-cluster.md)
    -   [Using the JDBC and ODBC Drivers to Connect to the Cluster](using-the-jdbc-and-odbc-drivers-to-connect-to-the-cluster.md)
        -   [Development Specifications](development-specifications.md)
        -   [Downloading the JDBC or ODBC Driver](downloading-the-jdbc-or-odbc-driver.md)
        -   [Using a JDBC Driver to Connect to the Database](using-a-jdbc-driver-to-connect-to-the-database.md)
        -   [Using an ODBC Driver to Connect to the Database](using-an-odbc-driver-to-connect-to-the-database.md)

    -   [Using the Third-Party Function Library psycopg2 of Python to Connect to a Cluster](using-the-third-party-function-library-psycopg2-of-python-to-connect-to-a-cluster.md)
    -   [Connecting to a Cluster Using IAM Authentication](connecting-to-a-cluster-using-iam-authentication.md)
        -   [Overview](overview.md)
        -   [Granting an IAM Account the DWS Database Access Permission](granting-an-iam-account-the-dws-database-access-permission.md)
        -   [Creating an IAM User Credential](creating-an-iam-user-credential.md)
        -   [Configuring the JDBC Connection to Connect to a Cluster Using IAM Authentication](configuring-the-jdbc-connection-to-connect-to-a-cluster-using-iam-authentication.md)

    -   [Managing Database Connections](managing-database-connections.md)

-   [Managing Snapshots](managing-snapshots.md)
    -   [Manually Creating a Snapshot](manually-creating-a-snapshot.md)
    -   [Setting the Automated Snapshot Policy](setting-the-automated-snapshot-policy.md)
    -   [Viewing Snapshot Information](viewing-snapshot-information.md)
    -   [Copying a Snapshot](copying-a-snapshot.md)
    -   [Restoring a Snapshot](restoring-a-snapshot.md)
    -   [Deleting a Snapshot](deleting-a-snapshot.md)

-   [Managing Parameter Groups](managing-parameter-groups.md)
-   [Managing MRS Data Sources](managing-mrs-data-sources.md)
    -   [Importing Data from MRS to DWS](importing-data-from-mrs-to-dws.md)
    -   [Creating an MRS Data Source Connection](creating-an-mrs-data-source-connection.md)
    -   [Updating the MRS Data Source Configuration](updating-the-mrs-data-source-configuration.md)

-   [Monitoring a Cluster](monitoring-a-cluster.md)
-   [Audit Logs](audit-logs.md)
    -   [Viewing Audit Logs of Key Operations on the Management Console](viewing-audit-logs-of-key-operations-on-the-management-console.md)
    -   [Configuring the Database Audit Log](configuring-the-database-audit-log.md)

-   [FAQs](faqs.md)
    -   [General FAQs](general-faqs.md)
        -   [What Is a Data Warehouse?](what-is-a-data-warehouse.md)
        -   [Why Are Data Warehouses Necessary?](why-are-data-warehouses-necessary.md)
        -   [What Scenarios Do Data Warehouses Apply To?](what-scenarios-do-data-warehouses-apply-to.md)
        -   [What Are the Differences Between Data Warehouses and the Hadoop Big Data Platform?](what-are-the-differences-between-data-warehouses-and-the-hadoop-big-data-platform.md)
        -   [Why Should I Use Public Cloud DWS?](why-should-i-use-public-cloud-dws.md)
        -   [What Are the Benefits of DWS?](what-are-the-benefits-of-dws.md)
        -   [Should I Choose DWS or RDS on Public Cloud?](should-i-choose-dws-or-rds-on-public-cloud.md)
        -   [When Should I Use DWS and MRS?](when-should-i-use-dws-and-mrs.md)
        -   [Can DWS SQL on OBS Replace MRS?](can-dws-sql-on-obs-replace-mrs.md)
        -   [Is the Function of DWS the Same as That of Hive?](is-the-function-of-dws-the-same-as-that-of-hive.md)
        -   [Can I Batch Create Data Warehouses?](can-i-batch-create-data-warehouses.md)
        -   [What Do I Do If I Fail to Create a Data Warehouse Cluster?](what-do-i-do-if-i-fail-to-create-a-data-warehouse-cluster.md)
        -   [Does DWS Support Third-party Clients and JDBC and ODBC Drivers?](does-dws-support-third-party-clients-and-jdbc-and-odbc-drivers.md)
        -   [What Are the Differences Between Data Formats Supported by an OBS Foreign Table?](what-are-the-differences-between-data-formats-supported-by-an-obs-foreign-table.md)
        -   [How Can I Upgrade or Downgrade DWS?](how-can-i-upgrade-or-downgrade-dws.md)
        -   [How Can I Clear and Reclaim the Storage Space?](how-can-i-clear-and-reclaim-the-storage-space.md)
        -   [What Is User Quota?](what-is-user-quota.md)

    -   [Security FAQs](security-faqs.md)
        -   [Is My Data Secure in DWS?](is-my-data-secure-in-dws.md)
        -   [What Security Protection Measures Are Used in DWS?](what-security-protection-measures-are-used-in-dws.md)

    -   [Connection and Access FAQs](connection-and-access-faqs.md)
        -   [What Should I Do If I Cannot Connect to a Data Warehouse Cluster?](what-should-i-do-if-i-cannot-connect-to-a-data-warehouse-cluster.md)
        -   [Does DWS Support Access to Sample Data?](does-dws-support-access-to-sample-data.md)
        -   [No Failure Message Is Displayed After the EIP Is Unbound When DWS Is Connected Over the Internet](no-failure-message-is-displayed-after-the-eip-is-unbound-when-dws-is-connected-over-the-internet.md)

    -   [Data Loading](data-loading.md)
        -   [How Can I Store Data to DWS?](how-can-i-store-data-to-dws.md)
        -   [How Much Service Data Can a Data Warehouse Store?](how-much-service-data-can-a-data-warehouse-store.md)

    -   [Scale-Out FAQs](scale-out-faqs.md)
        -   [Can I Scale Out a Cluster?](can-i-scale-out-a-cluster.md)
        -   [Can I Use the Data Warehouse Cluster During Cluster Scale-out?](can-i-use-the-data-warehouse-cluster-during-cluster-scale-out.md)

    -   [Performance FAQs](performance-faqs.md)
        -   [Why Is the Performance of DWS Worse Than That of a Single-Server Database in Extreme Scenarios?](why-is-the-performance-of-dws-worse-than-that-of-a-single-server-database-in-extreme-scenarios.md)


-   [Error Code Reference](error-code-reference.md)
-   [Glossary](glossary.md)
