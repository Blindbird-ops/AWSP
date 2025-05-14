.. _a2_diy:

===
DIY
===

After completing the lab, the player does DIY by taking the following steps.

#.  Select **DIY** to begin the activity.

    .. image:: static/5.4diyP1.png
       :alt: Placeholder screenshot for A2 DIY Step 1 (Select DIY)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In the **Plan** interface:
    * Read **DIY ACTIVITIES**.
    * Read **SOLUTION VALIDATION METHOD**.
    * Select **Open AWS Console**.

    .. image:: static/5.4diyP2.png
       :alt: Placeholder screenshot for A2 DIY Step 2 (Read Goals and Open Console)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **AWS Console**, find and select **EC2**.

    .. image:: static/5.4diyP3.png
       :alt: Placeholder screenshot for A2 DIY Step 3 (Find and Select EC2 in Console)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Select **Launch instance**.

    .. image:: static/5.4diyP4.png
       :alt: Placeholder screenshot for A2 DIY Step 4 (Select Launch Instance button)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Choose an Amazon Machine Image (AMI)**:
    * Select **Amazon Linux 2 AMI (HVM) - Kernel 5.10, SSD Volume Type**.
    * Select **Select**.

    .. image:: static/5.4diyP5.png
       :alt: Placeholder screenshot for A2 DIY Step 5 (Choose AMI)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Choose an Instance Type**:
    * Select ``t2.micro``.
    * Then select **Next: Configure Instance Details**.

    .. image:: static/5.4diyP6.png
       :alt: Placeholder screenshot for A2 DIY Step 6 (Choose Instance Type)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Configure Instance Details**:
    * Select **VPC**.
    * Choose **Subnet** different from the subnet used in Practice.

    .. image:: static/5.4diyP7.png
       :alt: Placeholder screenshot for A2 DIY Step 7 (Configure Instance Details - Subnet)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Advanced Details**:
    * Select **As file**.
    * Select **Select file** and download the file ``user-data``.
    * Select **Next: Add Storage**.

    .. image:: static/5.4diyP8.png
       :alt: Placeholder screenshot for A2 DIY Step 8 (Advanced Details - User Data)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Add Storage**, select **Next: Add Tags**.

    .. image:: static/5.4diyP9.png
       :alt: Placeholder screenshot for A2 DIY Step 9 (Add Storage)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Add Tags**, select **Next: Configure Security Group**.
#.  In **Configure Security Group**, create a security group:
    * For **Security group name**, enter ``Security-Group-Lab-2``.
    * For **Description**, enter ``HTTP Group Lab 2``.
    * For **Rule**, select **HTTP**.
    * Select **Review and Launch**.

    .. image:: static/5.4diyP10.png
       :alt: Placeholder screenshot for A2 DIY Step 11 (Configure Security Group)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Review Instance Launch**, double check details and select **Launch**.

    .. image:: static/5.4diyP11.png
       :alt: Placeholder screenshot for A2 DIY Step 12 (Review and Launch)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **Select an existing key pair or create a new key pair**:
    * Select **Proceed without a key pair**.
    * Select **I acknowledge…**.
    * Select **Launch Instances**.

    .. image:: static/5.4diyP12.png
       :alt: Placeholder screenshot for A2 DIY Step 13 (Key Pair selection)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Select **View Instances**.

    .. image:: static/5.4diyP13.png
       :alt: Placeholder screenshot for A2 DIY Step 14 (View Instances)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  After creating 2 **Amazon EC2 Instance**, copy both **Instance ID**.

    .. image:: static/5.4diyP14.png
       :alt: Placeholder screenshot for A2 DIY Step 15 (Copy Instance IDs)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Paste **Instance ID in AZ1** into the validation form.

    .. image:: static/5.4diyP15.png
       :alt: Placeholder screenshot for A2 DIY Step 16 (Paste ID in AZ1)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Paste **Instance ID in AZ2** into the validation form.

    .. image:: static/5.4diyP16.png
       :alt: Placeholder screenshot for A2 DIY Step 17 (Paste ID in AZ2)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Select **VALIDATE**.

    .. image:: static/5.4diyP17.png
       :alt: Placeholder screenshot for A2 DIY Step 18 (Select VALIDATE)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  After selecting **VALIDATE**, if **VALIDATION MESSAGE** contains "Success! …" is complete.

    .. image:: static/5.4diyP18.png
       :alt: Placeholder screenshot for A2 DIY Step 19 (Validation Success message)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Select **EXIT** (from validation).

    .. image:: static/5.4diyP19.png
       :alt: Placeholder screenshot for A2 DIY Step 20 (Select EXIT)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  In **ASSIGNMENT**, select **COLLECT** (rewards).

    .. image:: static/5.4diyP20.png
       :alt: Placeholder screenshot for A2 DIY Step 21 (Collect Rewards)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/

#.  Get rewarded.

    .. image:: static/5.4diyP21.png
       :alt: Placeholder screenshot for A2 DIY Step 22 (Get rewarded - final step)
       :align: center
       :width: 600px
       :target: https://000300.awsstudygroup.com/5-amazonec2/5.4-diy/
