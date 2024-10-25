1. On the **Azure portal** search for **Microsoft Entra ID** **(1)** in the search bar and select **Azure Virtual Desktop** **(2)** from the suggestions.
1. Click on **Users** under Manage blade in left hand side pane.
1. Click on **New user** and select **Create new user**.
1. Enter the following parameters and click on **Next:Prperties(3)**
    - **User principal name** : avdtrial(1)
    - **Display Name** - avdtrial(2)
    >Note:- Copy the Auto-generated password on a text editor such as notepad as it will be used to login and reset the password.
1. Click on **Next Assignments**.
1. Click on **+ Add role**.
1. Search for **Global Administrator(1)** and click on **Global Administrator(2)** from the list and click on **Select(3)**.
1. Click on Review + create.
1. Click on Create.
1. Once created click on refresh button and click on Copy to clipboard button to copy the User principal name of the user created and paste it in the notepad.
1. Click on Groups under manage blade in the left hand side pane.
1. Click on AAD DC Administrators Group.
1. Click on 1 besides User(s).
1. Click on + Add members.
1. Click on avdtrial from the list of users and then click on select.



1. On the **Azure portal** search for **Subscriptions** **(1)** in the search bar and select **Subscriptions** **(2)** from the suggestions.
1. Click on the available Subscription.
1. Click on Access control (IAM) on the left hand side pade.
1. Click on Add and select Add role assignment.
1. Click on Privilaged Administrator roles and select **owner**.
1. Click on Next.
1. Click on + Select members.
1. click on avd trial user from the list and click on select.
1. Click on next.
1. select Allow user to assign all roles (highly priviledged) for what user can do and click on review+ assign.
1. click on review + assign.
1. open inPrivate windows in Microsoft edge.
1. Go to [Azure Login](portal.azure.com) page.
1. enter the user principal name of the user created and click on next.
1. Enter the password that you copied in 4th step and click on sign in.
1. Enter the same password in the current password field of Update your password page.
1. Enter any new password that you want to assign to the Entra user that is created in the rest of the two fields.
>note: Make sure to save that password in a text editor like notepad as it will be used to perform the whole lab.
1. Click on Sign in.
>**Note:** If there's a popup entitled **Stay signed in?** with buttons for **No** and **Yes** - Choose **No**.
   
   ![](media/w26.png)

>**Note:** If there's another popup entitled **Welcome to Microsoft Azure** with buttons for **Get Started** and **Cancel** - Choose **Cancel**.
   
   >**Note:** If there's another popup entitled **Help us protect your account** click **Skip for now (14 days until this is required)**
