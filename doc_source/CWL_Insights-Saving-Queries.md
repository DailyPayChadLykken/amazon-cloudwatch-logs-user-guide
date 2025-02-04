# Saving and re\-running CloudWatch Logs Insights queries<a name="CWL_Insights-Saving-Queries"></a>

After you create a query, you can save it, and run it again later\. Queries are saved in a folder structure, so you can organized them\. You can save as many as 1000 queries per region and per account\.

To save a query, you must be logged into a role that has the permission `logs:PutQueryDefinition`\. To see a list of your saved queries, you must be logged into a role that has the permission`logs:DescribeQueryDefinitions`\.

**To save a query**

1. Open the CloudWatch console at [https://console\.aws\.amazon\.com/cloudwatch/](https://console.aws.amazon.com/cloudwatch/)\.

1. In the navigation pane, choose **Logs**, and then choose **Logs Insights**\.

1. In the query editor, create a query\.

1. Choose **Save**\.

   If you don't see a **Save** button, you need to change to the new design for the CloudWatch Logs console\. To do so:

   1. In the navigation pane, choose **Log groups**\.

   1. Choose **Try the new design**\.

   1. In the navigation pane, choose **Insights** and return to step 3 of this procedure\.

1. Enter a name for the query\.

1. \(Optional\) Choose a folder where you want to save the query\. Select **Create new** to create a folder\. If you create a new folder, you can use slash \(/\) characters in the folder name to define a folder structure\. For example, naming a new folder **folder\-level\-1/folder\-level\-2** creates a top\-level folder called **folder\-level\-1**, with another folder called **folder\-level\-2** inside that folder\. The query is saved in **folder\-level\-2**\.

1. \(Optional\) Change the query's log groups or query text\.

1. Choose **Save**\.

**To run a saved query**

1. Open the CloudWatch console at [https://console\.aws\.amazon\.com/cloudwatch/](https://console.aws.amazon.com/cloudwatch/)\.

1. In the navigation pane, choose **Logs**, and then choose **Logs Insights**\.

1. On the right, choose **Queries**\.

1. Select your query from **Saved queries** list\. It appears in the query editor\.

1. Choose **Run**\.

**To save a new version of a saved query**

1. Open the CloudWatch console at [https://console\.aws\.amazon\.com/cloudwatch/](https://console.aws.amazon.com/cloudwatch/)\.

1. In the navigation pane, choose **Logs**, and then choose **Logs Insights**\.

1. On the right, choose **Queries**\.

1. Select your query from **Saved queries** list\. It appears in the query editor\.

1. Modify the query\. If you need to run it to check your work, choose **Run query**\.

1. When you are ready to save the new version, choose **Actions**, **Save as**\.

1. Enter a name for the query\.

1. \(Optional\) Choose a folder where you want to save the query\. Select **Create new** to create a folder\. If you create a new folder, you can use slash \(/\) characters in the folder name to define a folder structure\. For example, naming a new folder **folder\-level\-1/folder\-level\-2** creates a top\-level folder called **folder\-level\-1**, with another folder called **folder\-level\-2** inside that folder\. The query is saved in **folder\-level\-2**\.

1. \(Optional\) Change the query's log groups or query text\.

1. Choose **Save**\.

To delete a query, you must be logged in to a role that has the `logs:DeleteQueryDefinition` permission\.

**To edit or delete a saved query**

1. Open the CloudWatch console at [https://console\.aws\.amazon\.com/cloudwatch/](https://console.aws.amazon.com/cloudwatch/)\.

1. In the navigation pane, choose **Logs**, and then choose **Logs Insights**\.

1. On the right, choose **Queries**\.

1. Select your query from **Saved queries** list\. It appears in the query editor\.

1. Choose **Actions**, **Edit** or **Actions**, **Delete**\.