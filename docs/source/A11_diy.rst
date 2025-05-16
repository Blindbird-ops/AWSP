.. _a11_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **DIY** interface:

   * Read **DIY ACTIVITIES**.
   * Read **SOLUTION VALIDATION METHOD**.
   * Select **Open AWS Console**.

   .. image:: static/14.4diyP1.png
      :alt: DIY interface showing instructions and Open AWS Console button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/14.4diyP2.png
      :alt: AWS Console showing EC2 service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In **EC2** interface:

   * Select **Instances**.

   .. image:: static/14.4diyP3.png
      :alt: EC2 interface showing Instances link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * View instances.

   .. image:: static/14.4diyP4.png
      :alt: EC2 interface showing instances list.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In **EC2** interface:

   * Select **Security Groups**.

   .. image:: static/14.4diyP5.png
      :alt: EC2 interface showing Security Groups link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In **EC2 Security Groups** interface: {# Clarifying interface based on likely flow #}

   * View **Security Groups**.

   .. image:: static/14.4diyP6.png
      :alt: EC2 Security Groups interface showing list of security groups.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In **EC2 Security Groups** interface: {# Clarifying interface #}

   * Select **Create security group**.

   .. image:: static/14.4diyP7.png
      :alt: EC2 Security Groups interface showing Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * For **Security group name**, enter ``PetModels-EFS-1-SG``.

   .. image:: static/14.4diyP8.png
      :alt: Create security group interface showing name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * For **Description**, enter ``Restrict access to webservers only``. {# Correcting "Restric" #}

   .. image:: static/14.4diyP9.png
      :alt: Create security group interface showing description field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **PetModels VPC**.

   .. image:: static/14.4diyP10.png
      :alt: Create security group interface showing VPC selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **Add rule**.

   .. image:: static/14.4diyP11.png
      :alt: Create security group interface showing Add rule button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface (Inbound rules):

   * In **Inbound rules**, select **NFS**.

   .. image:: static/14.4diyP12.png
      :alt: Create security group inbound rules showing NFS type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface (Inbound rules):

   * Select **webserver Security group** (as the source).

   .. image:: static/14.4diyP13.png
      :alt: Create security group inbound rules showing source security group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **Create security group**.

   .. image:: static/14.4diyP14.png
      :alt: Create security group interface showing Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Security groups** interface:

   * View **Security group name** (just created).
   * View the **Inbound rules**.

   .. image:: static/14.4diyP15.png
      :alt: Security groups interface showing newly created security group details.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **AMIs**.

   .. image:: static/14.4diyP16.png
      :alt: EC2 interface showing AMIs link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 AMIs** interface:

   * Select **GameServer** (the AMI created in Practice).

   .. image:: static/14.4diyP17.png
      :alt: EC2 AMIs interface showing GameServer AMI selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 AMIs** interface:

   * Select **Refresh**.

   .. image:: static/14.4diyP18.png
      :alt: EC2 AMIs interface showing Refresh button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 AMIs** interface:

   * View **Status** (should be ``available``).

   .. image:: static/14.4diyP19.png
      :alt: EC2 AMIs interface showing AMI status.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Launch Templates**.

   .. image:: static/14.4diyP20.png
      :alt: EC2 interface showing Launch Templates link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch templates** interface:

   * Select **Create launch templates**.

   .. image:: static/14.4diyP21.png
      :alt: EC2 launch templates interface showing Create launch templates button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create launch template** interface:

   * For **Launch template name**, enter ``GameServerTemplate``. {# Correcting "Lauch" #}

   .. image:: static/14.4diyP22.png
      :alt: Create launch template interface showing name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create launch template** interface:

   * For **Template version description**, enter ``Regular customer game server template``.

   .. image:: static/14.4diyP23.png
      :alt: Create launch template interface showing description field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * Select **My AMIs**.

   .. image:: static/14.4diyP24.png
      :alt: Create launch template interface showing My AMIs link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * Select **Owned by me**.

   .. image:: static/14.4diyP25.png
      :alt: Create launch template interface showing Owned by me link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * In **Amazon Machine Image (AMI)**, select **GameServer** (your custom AMI).

   .. image:: static/14.4diyP26.png
      :alt: Create launch template interface showing AMI selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * In **Instance type**, select **t2.nano**.

   .. image:: static/14.4diyP27.png
      :alt: Create launch template interface showing instance type selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * Select **Create new key pair**.

   .. image:: static/14.4diyP28.png
      :alt: Create launch template interface showing Create new key pair link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **EC2 launch template** interface:

   * Select **Select existing security group**.

   .. image:: static/14.4diyP29.png
      :alt: Create launch template interface showing Select existing security group option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create key pair** interface:

   * For **Key pair name**, enter ``GameServerKeyPair``.

   .. image:: static/14.4diyP30.png
      :alt: Create key pair interface showing key pair name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **Create scheduled action** interface: {# This is step 31, no image #}

   * For **Name**, enter ``SecondWaveOfRegulars``.
   * For **Desired capacity**, enter ``0``.
   * For **Min**, enter ``0``.
   * For **Max**, enter ``0``.
   * For **Recurrence**, select **Every day**.
   * For **Specific start time**, select date and year and select ``01:00``.
   * Select **Create**.

#. In the **DIY** interface: {# This is step 32, with image 32 #}

   * For **Your Auto Scaling group name**, enter ``RegularCustomerGameServer``.
   * For **scheduled-action-name**, enter ``SecondWaveOfRegulars``.
   * Select **VALIDATE**.

   .. image:: static/14.4diyP31.png
      :alt: DIY interface showing ASG name and scheduled action name entered for validation.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. After selecting **VALIDATE**: {# This is step 33, with image 33 #}

   * **VALIDATION MESSAGE** appears **Nice!…**.
   * Select **EXIT** to exit.

   .. image:: static/14.4diyP32.png
      :alt: DIY interface showing validation success message and Exit button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. In the **city view**: {# This is step 34, with image 34 #}

   * Select **ASSIGNMENTS**.
   * Select **COLLECT**.

   .. image:: static/14.4diyP33.png
      :alt: City view showing Assignments and Collect options.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. Select **NEXT**. {# This is step 35, with image 35 #}

   .. image:: static/14.4diyP34.png
      :alt: City view showing Next button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. Select **COLLECT**. {# This is step 36, with image 36 #}

   .. image:: static/14.4diyP35.png
      :alt: City view showing Collect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}

#. **Congratulations to the award-winning player!** {# This is step 37, with image 37 - making 36 total #}

   .. image:: static/14.4diyP36.png
      :alt: Congratulations screen for completing the lab.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/11-scaling/11.4-diy/ {# Replace with actual URL #}
