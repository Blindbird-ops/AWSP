.. _a6_diy:

===
DIY
===

Here’s the full set of steps:

#. Interface DIY:

   * Read **DIY ACTIVITIES**.
   * Read **SOLUTION VALIDATION METHOD**.

   .. image:: static/A6D01.png
      :alt: DIY interface with activities and validation method instructions.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. Select “**Open AWS Console**”.

   .. image:: static/A6D02.png
      :alt: AWS console button highlighted.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **VPC**.
   * Select **VPC**.
   * Select **Your VPCs**.
   * View the VPC.

   .. image:: static/A6D03.png
      :alt: AWS console showing VPC service and Your VPCs list.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/A6D04.png
      :alt: AWS console showing EC2 service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **Developer Server**.
   * Select **Details**.
   * View **VPC ID**.
   * Select **Connect**.

   .. image:: static/A6D05.png
      :alt: EC2 interface showing instances, Developer Server selected, details viewed, and Connect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the “**Connect to instance**” interface:

   * Select “**EC2 Instance Connect**”.
   * Select **Connect**.

   .. image:: static/A6D06.png
      :alt: Connect to instance options, EC2 Instance Connect selected and Connect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **CLI** interface:

    * Enter ``ping 172.31.0.10``.
    * View results.

   .. image:: static/A6D07.png
      :alt: CLI with ping command and results.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

    * Select **Developer Server**.
    * Select **Subnet ID**.

   .. image:: static/A6D08.png
      :alt: Developer server details showing Subnet ID link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Subnet** interface:

    * Select **DeveloperPublicSubnet1**.
    * Select **Route table**.

   .. image:: static/A6D09.png
      :alt: Subnet details page showing route table link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Route Tables** interface:

    * Select **DeveloperPublicSubnet1**.
    * Select **Routes**.
    * View the route rules.

   .. image:: static/A6D10.png
      :alt: Developer Public Route Table details showing Routes tab and existing rules.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **VPC** interface:

    * Select **Peering Connections**.
    * Select “**Create peering connection**”.

   .. image:: static/A6D11.png
      :alt: VPC menu showing Peering Connections and Create button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Peering Connection Settings** interface:

    * For **Name**, enter ``Developer <> Finance``.
    * For **VPC ID**, select your Dev VPC.
    * Under **Account**, select **My account**.
    * Under **Region**, select **This Region (us-east-1)**.

   .. image:: static/A6D12.png
      :alt: Configure peering connection settings.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Peering Connection Settings** interface:

    * Select “**Create peering connection**”.

   .. image:: static/A6D13.png
      :alt: Clicking the Create peering connection button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. View **Initialization result**.

   .. image:: static/A6D14.png
      :alt: Peering connection created, status pending acceptance.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **VPC** interface:

   * Select **Peering Connections**.
   * Select **Developer <> Finance**.
   * View **Status**.
   * Select **Actions** → **Accept request**.

   .. image:: static/A6D15.png
      :alt: Peering connections list, select connection, view status, select accept action.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the “**Accept VPC peering connection request**” interface:

   * Select “**Accept request**”.

   .. image:: static/A6D16.png
      :alt: Confirmation dialog to accept the peering request.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. View **Result** (peering connection should be active).

   .. image:: static/A6D17.png
      :alt: Peering connection status is now active.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **VPC** interface:

   * Select **Route Tables**.
   * Select **DeveloperPublicSubnet1**.
   * Select **Routes**.
   * View the route rules.
   * Select **Edit routes**.

   .. image:: static/A6D18.png
      :alt: Navigate to Developer Public Route Table and select edit routes.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Edit Routes** interface:

   * Select **Add route**.
   * In **Destination**, enter ``172.31.0.0/16``.
   * For **Target**, select **Developer <> Finance**.
   * Select **Save changes**.

   .. image:: static/A6D19.png
      :alt: Add route to Finance VPC in Developer RT.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. View **Results after initialization** (Developer RT updated).

   .. image:: static/A6D20.png
      :alt: Developer Route Table with the new route added.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **VPC** interface:

   * Select **Route Tables**.
   * Select **FinancePrivateSubnet1**.
   * Select **Routes**.
   * View the route rules.
   * Select **Edit routes**.

   .. image:: static/A6D21.png
      :alt: Navigate to Finance Private Route Table and select edit routes.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Edit Routes** interface:

   * Select **Add route**.
   * In **Destination**, enter ``192.168.0.10/32``.
   * In **Target**, select **Developer <> Finance**.
   * Select **Save changes**.

   .. image:: static/A6D22.png
      :alt: Add route to Developer IP in Finance RT.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. View **Initialization result** (Finance RT updated).

   .. image:: static/A6D23.png
      :alt: Finance Route Table with the new route added.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **Developer Server**.
   * Select **Connect**.

   .. image:: static/A6D24.png
      :alt: Select Developer Server and Connect.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the “**Connect to instance**” interface:

   * Select “**EC2 Instance Connect**”.
   * Select **Connect**.

   .. image:: static/A6D25.png
      :alt: Connect to instance via EC2 Instance Connect.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Developer Server CLI**:

    * Enter ``ping 172.31.0.10``.
    * View results.

   .. image:: static/A6D26.png
      :alt: Ping command and results in Developer Server CLI after route changes.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **Financial Services Server**.
   * Select **Security**.
   * Select **Security groups**.

   .. image:: static/A6D27.png
      :alt: Navigate to Financial Services Server security groups.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In **FinanceServerSecurityGroup**:

   * Select **Inbound rules**.
   * View the inbound rules.
   * Select **Edit inbound rules**.

   .. image:: static/A6D28.png
      :alt: View and edit inbound rules for Finance server security group.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Edit Inbound Rules** interface:

   * Select **Add rule**.
   * For **Type**, choose **All ICMP-IPv4**.
   * For **Source**, choose **Custom**.
   * Enter ``192.168.10.32``.
   * Select **Save rules**.

   .. image:: static/A6D29.png
      :alt: Add ICMP rule allowing traffic from specified source IP.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. View **Results after initialization** (updated security group rules).

   .. image:: static/A6D30.png
      :alt: Security group inbound rules showing the new ICMP rule.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **CLI** (Developer Server CLI):

    * Enter ``ping 172.31.0.10``.
    * View results.

   .. image:: static/A6D31.png
      :alt: Ping command and successful results in Developer Server CLI after security group change.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **DIY** interface:

   * Enter Developer instance ID.
   * Enter Finance instance ID.
   * Then, select **VALIDATE**.

   .. image:: static/A6D32.png
      :alt: DIY interface with fields for instance IDs and validate button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **Developer Server**.
   * Select **Details**.
   * Copy the **Instance ID**.

   .. image:: static/A6D33.png
      :alt: Developer server details showing instance ID to copy.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **Financial Services Server**.
   * Select **Details**.
   * Copy the **Instance ID**.

   .. image:: static/A6D34.png
      :alt: Financial Services server details showing instance ID to copy.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **DIY** interface:

   * Paste both Instance IDs into the **VALIDATION FORM**.
   * Select **VALIDATE**.

   .. image:: static/A6D35.png
      :alt: DIY interface with instance IDs pasted in validation form.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **Validation Message** interface:

   * The message “You did it!…” appears.
   * Select **EXIT** to exit.

   .. image:: static/A6D36.png
      :alt: Validation success message.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **City** interface:

   * Select **ASSIGNMENTS**.
   * Select **COLLECT**.

   .. image:: static/A6D37.png
      :alt: City interface showing Assignments and Collect options.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **City** interface:

    * Select **NEXT**.

   .. image:: static/A6D38.png
      :alt: Selecting NEXT after collecting assignment.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. In the **City** interface:

    * Select **COLLECT**.

   .. image:: static/A6D39.png
      :alt: Selecting COLLECT again.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}

#. Congratulations to the player for completing the lab!

   .. image:: static/A6D40.png
      :alt: Congratulations screen.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/  {# Replace with actual URL #}
