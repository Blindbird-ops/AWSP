.. _a5_diy: # Replace 'a5_diy' if a different label is preferred

===
DIY
===

After completing the lab, the player does DIY.

#.  In the **DIY** interface: {# Omitted descriptive line #}

    * Read **DIY ACTIVITIES**.
    * Read **SOLUTION VALIDATION METHOD**.

    .. image:: static/A5D1.png
       :alt: Placeholder screenshot for A5 DIY Step 1 (Read Goals)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Go to the **AWS Pricing Calculator**.

    .. image:: static/A5D2.png
       :alt: Placeholder screenshot for A5 DIY Step 2 (Go to Pricing Calculator)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Select **Create estimate**.

    .. image:: static/A5D3.png
       :alt: Placeholder screenshot for A5 DIY Step 3 (Create Estimate)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **My Estimate**:

    * Select **Add group**.

    .. image:: static/A5D4.png
       :alt: Placeholder screenshot for A5 DIY Step 4 (Add Group)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Add group**:

    * Group name, enter **Web Servers**.
    * Select **Add group**.

    .. image:: static/A5D5.png
       :alt: Placeholder screenshot for A5 DIY Step 5 (Enter Group Name and Add Group)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In the **Web Servers** interface:

    * Select **Add service**.

    .. image:: static/A5D6.png
       :alt: Placeholder screenshot for A5 DIY Step 6 (Add Service)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Add service**:

    * Search **EC2**.
    * Select **Configure**.

    .. image:: static/A5D7.png
       :alt: Placeholder screenshot for A5 DIY Step 7 (Search EC2 and Configure)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Configure Amazon EC2**:

    * Description, enter **Web Server Estimate**.
    * Region, select **US East (N. Virginia)**.
    * In **EC2 instance specifications**, select **Linux**.

    .. image:: static/A5D8.png
       :alt: Placeholder screenshot for A5 DIY Step 8 (Configure EC2 Basic)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In the **Workload** interface:

    * Select **Daily spike traffic**.

    .. image:: static/A5D9.png
       :alt: Placeholder screenshot for A5 DIY Step 9 (Select Workload)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Daily spike pattern, **Workload days** section:

    * Choose the days of the week.

    .. image:: static/A5D10.png
       :alt: Placeholder screenshot for A5 DIY Step 10 (Choose Workload Days)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Daily spike pattern:

    * Baseline, enter ``2``.
    * Peak, enter ``4``.
    * Duration of peak, enter ``8`` and ``0``.

    .. image:: static/A5D11.png
       :alt: Placeholder screenshot for A5 DIY Step 11 (Configure Daily Spike Pattern)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **EC2 Instances**:

    * Select **t2.micro**.

    .. image:: static/A5D12.png
       :alt: Placeholder screenshot for A5 DIY Step 12 (Select Instance Type)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Pricing strategy**:

    * Pricing model, select **On-demand**.
    * Select **Show calculations**.
    * Select **estimate workload hours**.

    .. image:: static/A5D13.png
       :alt: Placeholder screenshot for A5 DIY Step 13 (Configure Pricing Strategy)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Amazon Elastic Block Storage (EBS)**:

    * Storage for each EC2 instance, select **General Purpose SSD (gp2)**.
    * Storage amount, enter ``30``.
    * Snapshot Frequency, enter **Weekly**.
    * Amount changed per snapshot, enter **1**.

    .. image:: static/A5D14.png
       :alt: Placeholder screenshot for A5 DIY Step 14 (Configure EBS)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  View results **Estimated workload hours**.

    .. image:: static/A5D15.png
       :alt: Placeholder screenshot for A5 DIY Step 15 (View Estimated Workload Hours)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Data Transfer**:
    * Inbound Data Transfer, select **Internet (free)**.
    * Select ``1``.
    * Select **TB per month**.

    .. image:: static/A5D16.png
       :alt: Placeholder screenshot for A5 DIY Step 16 (Configure Inbound Data Transfer)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In **Data Transfer**:

    * Outbound Data Transfer, select **Internet ($0.05 - $0.09 per GB)**.
    * Select ``100``.
    * Select **TB per month**.

    .. image:: static/A5D17.png
       :alt: Placeholder screenshot for A5 DIY Step 17 (Configure Outbound Data Transfer)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Select **Show calculations**.

    .. image:: static/A5D18.png
       :alt: Placeholder screenshot for A5 DIY Step 18 (Show Calculations)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  View and select **Add to my estimate**.

    .. image:: static/A5D19.png
       :alt: Placeholder screenshot for A5 DIY Step 19 (Add to My Estimate)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  In the **Web Servers** interface: {# Note: User had "16 In the Save estimate" here, renumbering #}

    * Select **Share**.

    .. image:: static/A5D20.png
       :alt: Placeholder screenshot for A5 DIY Step 20 (Share Estimate)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}

#.  Congratulations to the player receiving the reward. {# This is Step 21 #}

    .. image:: static/A5D21.png
       :alt: Placeholder screenshot for A5 DIY Step 21 (Congratulations)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/8-pricingcalculator/8.4-diy/ {# Replace with actual URL for A5 DIY #}
