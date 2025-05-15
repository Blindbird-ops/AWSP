.. _a4_diy: # Replace 'a4_diy' if a different label is preferred

===
DIY
===

After completing the lab, the player does DIY.

#.  Select **DIY**.

    .. image:: static/7.4diyP1.png
       :alt: Placeholder screenshot for A4 DIY Step 1 (Select DIY)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  Read **SOLUTION VALIDATION METHOD**. {# Omitted descriptive lines #}

    .. image:: static/7.4diyP2.png
       :alt: Placeholder screenshot for A4 DIY Step 2 (Read Validation Method)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In the **AWS Console** page, find and select **EC2**.

    .. image:: static/7.4diyP3.png
       :alt: Placeholder screenshot for A4 DIY Step 3 (Go to EC2 in Console for DIY)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  Select **Instances**.

    .. image:: static/7.4diyP4.png
       :alt: Placeholder screenshot for A4 DIY Step 4 (Select Instances)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  Select **Security**.

    .. image:: static/7.4diyP5.png
       :alt: Placeholder screenshot for A4 DIY Step 5 (Select Security)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In **Security groups**, select **DbServerSecurityGroup**.

    .. image:: static/7.4diyP6.png
       :alt: Placeholder screenshot for A4 DIY Step 6 (Select DbServerSecurityGroup)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In the **Security Groups** interface:

    * Select **Edit inbound rules**.

    .. image:: static/7.4diyP7.png
       :alt: Placeholder screenshot for A4 DIY Step 7 (Edit Inbound Rules)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In the **Edit inbound rules** interface:

    * Type: select **MYSQL/Aurora**.
    * Protocol: select **TCP**.
    * Prot range: enter ``3306``.
    * Source: choose **Custom**.
    * Then select **Save rules**.

    .. image:: static/7.4diyP8.png
       :alt: Placeholder screenshot for A4 DIY Step 8 (Add Inbound Rule)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In the **Security groups** view, copy **Security group name**. {# Omitted descriptive lines #}

    .. image:: static/7.4diyP9.png
       :alt: Placeholder screenshot for A4 DIY Step 9 (Copy Security Group Name)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  In the **DIY** interface: {# Omitted descriptive lines #}

    * Paste **Security group name** into **VALIDATION FORM** in **Database Security Group name** field.

    .. image:: static/7.4diyP10.png
       :alt: Placeholder screenshot for A4 DIY Step 10 (Paste Security Group Name for Validation)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  Then select **VALIDATE**. {# Omitted descriptive lines #}

    .. image:: static/7.4diyP11.png
       :alt: Placeholder screenshot for A4 DIY Step 11 (Select VALIDATE)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  On **VALIDATION MESSAGE**, appears "Nice!You have properly configured your security!" and done **DIY**. Select **EXIT** to exit.

    .. image:: static/7.4diyP12.png
       :alt: Placeholder screenshot for A4 DIY Step 12 (Validation Success and Exit)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}

#.  Congratulations on completing lab 7.

    .. image:: static/7.4diyP13.png
       :alt: Placeholder screenshot for A4 DIY Step 13 (Congratulations)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/7-internetvpc/7.4-diy/ {# Replace with actual URL for A4 DIY #}
