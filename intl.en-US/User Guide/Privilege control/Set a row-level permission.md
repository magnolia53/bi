# Set a row-level permission {#task_hhz_d1y_5db .task}

The row-level permission setting must operate on datasets.

Currently, only in the workspace of Quick BI Pro can perform the row-level permission setting. The function in personal workspace is invalid.

1.   Log on to the Quick BI console. 
2.   Select a workspace, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9170/15502245051421_en-US.png)

 

    To create a new workspace, see Create a workspace.

3.   Click **Datasets** icon to enter the dataset management page. 
4.   Select a dataset and right-click or click the **Ellipsis** icon. 
5.   Select **Row-Level Permissions**. 
6.   Select **Enable Row-level Permission Control**. 
7.   Select fields, which are required to set row-level permission, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9170/15502245051427_en-US.png)

 

    Measure value is all the measurement fields in the dataset.  By controlling the measurement fields, different users can see different measurement results.

8.   In the **Permissions** list, click **province**. The province items are listed automatically, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9170/15502245051429_en-US.png)

 
9.   Select a member and set row-level permissions from the **province** item list, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9170/15502245051431_en-US.png)

 

    This member can only see the data in Beijing and Guangdong, and the data from other provinces are not visible to this member.

    **Note:** Even only one field of a dataset requires row-level permission control, you must set the list of field members who have the permission to access the controlled field on the controlled field of the dataset for all users in the organizational unit. If the list of field members is not set, the member is not allowed to access any data reports that generated by the dataset by default.

10.  Click **OK** to complete the row-level permission setting. 

## Example of row-level permission settings {#task_zdr_4cy_5db}

Select shipping\_type and province to perform the row-level permission settings.

1.   Enable the row-level permission function. 
2.   Select **shipping\_type** and **province** from the drop-down list, as shown in the following figure.![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9170/15502245051445_en-US.png)

 
3.   Select a member, for example, user1. 

    Set row-level permissions from shipping\_type items and province items.

4.   Select a member, for example, user2. 

    Set row-level permissions from shipping\_type items and province items.

5.   Click **OK** to complete the row-level permission setting. 

## Verify row-level permission settings {#task_nlh_xly_5db}

Different users can view different data in a same dashboard due to the row-level permission setting is performed.

If an organizational unit member has not been assigned with a dimension member that can be viewed, the report cannot be executed, and a message indicating that the member has no permission on a controlled field is displayed.

