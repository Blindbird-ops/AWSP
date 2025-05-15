.. _a6_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **DIY** interface:

   * Read **DIY ACTIVITIES**.
   * Read **SOLUTION VALIDATION METHOD**.

   .. image:: static/A6D1.png
      :alt: Placeholder screenshot for A6 DIY Step 1 (Read DIY Activities and Validation Method)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Open AWS Console**.

   .. image:: static/A6D2.png
      :alt: Placeholder screenshot for A6 DIY Step 2 (Select Open AWS Console)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **AWS Console** interface:

   * Find **VPC**.
   * Select **VPC**.

   .. image:: static/A6D3.png
      :alt: Placeholder screenshot for A6 DIY Step 3 (Find and Select VPC in Console)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **VPC** interface:

   * Select **Your VPCs**.

   .. image:: static/A6D4.png
      :alt: Placeholder screenshot for A6 DIY Step 4 (Select Your VPCs)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View your VPCs.

   .. image:: static/A6D5.png
      :alt: Placeholder screenshot for A6 DIY Step 5 (View VPCs List)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/A6D6.png
      :alt: Placeholder screenshot for A6 DIY Step 6 (Find and Select EC2 in Console)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **EC2** interface:

   * Select **Instances**.

   .. image:: static/A6D7.png
      :alt: Placeholder screenshot for A6 DIY Step 7 (Select Instances)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Developer Server**.

   .. image:: static/A6D8.png
      :alt: Placeholder screenshot for A6 DIY Step 8 (Select Developer Server)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Details** and view **VPC ID**.

   .. image:: static/A6D9.png
      :alt: Placeholder screenshot for A6 DIY Step 9 (View Developer Server Details including VPC ID)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Connect**.

   .. image:: static/A6D10.png
      :alt: Placeholder screenshot for A6 DIY Step 10 (Select Connect)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Connect to instance** interface:

   * Select **EC2 instance Connect**.

   .. image:: static/A6D11.png
      :alt: Placeholder screenshot for A6 DIY Step 11 (Select EC2 Instance Connect Method)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Connect**.

   .. image:: static/A6D12.png
      :alt: Placeholder screenshot for A6 DIY Step 12 (Select Connect Button)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **CLI** interface:

   * Enter ``ping 172.31.0.10``.

   .. image:: static/A6D13.png
      :alt: Placeholder screenshot for A6 DIY Step 13 (Enter Ping Command in CLI)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View results (initial ping should fail).

   .. image:: static/A6D14.png
      :alt: Placeholder screenshot for A6 DIY Step 14 (View Initial Ping Results - Failed)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **EC2** interface:

   * Select **Developer Server**.

   .. image:: static/A6D15.png
      :alt: Placeholder screenshot for A6 DIY Step 15 (Select Developer Server in EC2 List)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Subnet ID**.

   .. image:: static/A6D16.png
      :alt: Placeholder screenshot for A6 DIY Step 16 (Select Subnet ID)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Subnet** interface:

   * Select **DeveloperPublicSubnet1**.

   .. image:: static/A6D17.png
      :alt: Placeholder screenshot for A6 DIY Step 17 (Select Developer Public Subnet)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Route table**.

   .. image:: static/A6D18.png
      :alt: Placeholder screenshot for A6 DIY Step 18 (Select Route Table from Subnet)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Route tables** interface:

   * Select the route table named **DeveloperPublicSubnet1**.

   .. image:: static/A6D19.png
      :alt: Placeholder screenshot for A6 DIY Step 19 (Select Developer Public Route Table)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Routes** and view the route rules.

   .. image:: static/A6D20.png
      :alt: Placeholder screenshot for A6 DIY Step 20 (View Route Table Routes)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **VPC** interface:

   * Select **Peering Connections**.

   .. image:: static/A6D21.png
      :alt: Placeholder screenshot for A6 DIY Step 21 (Select Peering Connections in VPC Menu)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Create peering connection**.

   .. image:: static/A6D22.png
      :alt: Placeholder screenshot for A6 DIY Step 22 (Select Create Peering Connection)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Create peering connection** interface:

   * For **Name**, enter ``Developer <> Finance``.
   * Select **VPC ID** (Requester).
   * For **Account**, select **My account**.
   * For **Region**, select **This Region (us-east-1)**.

   .. image:: static/A6D23.png
      :alt: Placeholder screenshot for A6 DIY Step 23 (Configure Peering Connection Settings)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Create peering connection**.

   .. image:: static/A6D24.png
      :alt: Placeholder screenshot for A6 DIY Step 24 (Select Create Peering Connection Button)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View the initialization result (peering connection pending).

   .. image:: static/A6D25.png
      :alt: Placeholder screenshot for A6 DIY Step 25 (View Pending Peering Connection Status)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **VPC** interface:

   * Select **Peering Connections**.

   .. image:: static/A6D26.png
      :alt: Placeholder screenshot for A6 DIY Step 26 (Return to Peering Connections List)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Developer <> Finance** from the list.

   .. image:: static/A6D27.png
      :alt: Placeholder screenshot for A6 DIY Step 27 (Select the New Peering Connection)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View the status of the connection.

   .. image:: static/A6D28.png
      :alt: Placeholder screenshot for A6 DIY Step 28 (View Peering Connection Details and Status)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Actions**, then select **Accept request**.

   .. image:: static/A6D29.png
      :alt: Placeholder screenshot for A6 DIY Step 29 (Select Actions and Accept Request)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Accept VPC peering connection request** interface:

   * Select **Accept request**.

   .. image:: static/A6D30.png
      :alt: Placeholder screenshot for A6 DIY Step 30 (Confirm Accepting Peering Request)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View the result (peering connection should be active).

   .. image:: static/A6D31.png
      :alt: Placeholder screenshot for A6 DIY Step 31 (View Active Peering Connection Status)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **VPC** interface:

   * Select **Route Tables**.

   .. image:: static/A6D32.png
      :alt: Placeholder screenshot for A6 DIY Step 32 (Select Route Tables in VPC Menu)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select the route table named **DeveloperPublicSubnet1**.

   .. image:: static/A6D33.png
      :alt: Placeholder screenshot for A6 DIY Step 33 (Select Developer Public Route Table from List)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Routes** and view the route rules.

   .. image:: static/A6D34.png
      :alt: Placeholder screenshot for A6 DIY Step 34 (View Routes Tab)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Edit routes**.

   .. image:: static/A6D35.png
      :alt: Placeholder screenshot for A6 DIY Step 35 (Select Edit Routes)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **Edit routes** interface:

   * Select **Add route**.
   * In **Destination**, enter ``172.31.0.0/16``.
   * For **Target**, select the peering connection **Developer <> Finance**.

   .. image:: static/A6D36.png
      :alt: Placeholder screenshot for A6 DIY Step 36 (Add Route to Finance VPC in Developer RT)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select **Save changes**.

   .. image:: static/A6D37.png
      :alt: Placeholder screenshot for A6 DIY Step 37 (Save Route Table Changes)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. View the results after initialization (the new route should appear).

   .. image:: static/A6D38.png
      :alt: Placeholder screenshot for A6 DIY Step 38 (View Developer RT with New Route)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. In the **VPC** interface:

   * Select **Route Tables**.

   .. image:: static/A6D39.png
      :alt: Placeholder screenshot for A6 DIY Step 39 (Select Route Tables again for Finance RT)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/

#. Select the route table named **FinancePrivatesSubnet1**.

   .. image:: static/A6D40.png
      :alt: Placeholder screenshot for A6 DIY Step 40 (Select Finance Private Route Table)
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-connectingvpcs/9.4-diy/
