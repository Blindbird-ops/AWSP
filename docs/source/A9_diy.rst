.. _a9_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/12.4diyP1.png
      :alt: AWS Console showing EC2 service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * View the instance list.

   .. image:: static/12.4diyP2.png
      :alt: EC2 interface showing Instances list.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In **EC2** interface:

   * Select **Security Groups**.
   * View **Security Groups**.
   * Select **Create security group**.

   .. image:: static/12.4diyP3.png
      :alt: EC2 interface showing Security Groups and Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * For **Security group name**, enter ``PetModels-EFS-1-SG``.

   .. image:: static/12.4diyP4.png
      :alt: Create security group interface showing name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * For **Description**, enter ``Restrict access to webservers only``.

   .. image:: static/12.4diyP5.png
      :alt: Create security group interface showing description field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **PetModels VPC**.

   .. image:: static/12.4diyP6.png
      :alt: Create security group interface showing VPC selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **Add rule**.

   .. image:: static/12.4diyP7.png
      :alt: Create security group interface showing Add rule button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * In **Inbound rules**, select **NFS**.

   .. image:: static/12.4diyP8.png
      :alt: Create security group inbound rules showing NFS type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * In **Inbound rules**, for **Source**, select **webserver Security group**.

   .. image:: static/12.4diyP9.png
      :alt: Create security group inbound rules showing source security group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **Create security group**.

   .. image:: static/12.4diyP10.png
      :alt: Create security group interface showing Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Security groups** interface:

   * View **Security group name** (just created).
   * View the **Inbound rules**.

   .. image:: static/12.4diyP11.png
      :alt: Security groups interface showing newly created security group details.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **EFS**.
   * Select **EFS**.

   .. image:: static/12.4diyP12.png
      :alt: AWS Console showing EFS service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **EFS** interface:

   * Select **Create file system**.

   .. image:: static/12.4diyP13.png
      :alt: EFS interface showing Create file system button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create file system** interface:

   * For **Name**, enter ``PetModels-EFS-1``.

   .. image:: static/12.4diyP14.png
      :alt: Create file system interface showing name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create file system** interface:

   * For **VPC**, select **PetModels**.

   .. image:: static/12.4diyP15.png
      :alt: Create file system interface showing VPC selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create file system** interface:

   * Select **Regional**.

   .. image:: static/12.4diyP16.png
      :alt: Create file system interface showing Regional selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create file system** interface:

   * Select **Customize**.

   .. image:: static/12.4diyP17.png
      :alt: Create file system interface showing Customize button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File Systems** interface (Create file system - Configure optional settings):

   * In **Automatic backups**, uncheck **Enable automatic backups**.

   .. image:: static/12.4diyP18.png
      :alt: EFS optional settings showing automatic backups unchecked.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File Systems** interface (Create file system - Configure optional settings):

   * In **Transition into IA**, select **None**.

   .. image:: static/12.4diyP19.png
      :alt: EFS optional settings showing Transition into IA set to None.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File systems** interface (Create file system):

   * Select **Next**.

   .. image:: static/12.4diyP20.png
      :alt: EFS optional settings showing Next button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Uncheck security group of **us-east-1a**.

   .. image:: static/12.4diyP21.png
      :alt: EFS Network access showing removal of us-east-1a security group.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Select **Remove** the remaining AZs.

   .. image:: static/12.4diyP22.png
      :alt: EFS Network access showing removal of remaining AZs.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Select **us-east-1a**.

   .. image:: static/12.4diyP23.png
      :alt: EFS Network access showing selection of us-east-1a AZ.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Select **Subnet ID** for us-east-1a.

   .. image:: static/12.4diyP24.png
      :alt: EFS Network access showing selection of subnet for us-east-1a.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Select **Security group**.

   .. image:: static/12.4diyP25.png
      :alt: EFS Network access showing selection of security group.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Network access** interface (Create file system):

   * Select **Next**.

   .. image:: static/12.4diyP26.png
      :alt: EFS Network access showing Next button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File system policy** interface (Create file system):

   * Select **Next**.

   .. image:: static/12.4diyP27.png
      :alt: File system policy interface showing Next button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Create file system** interface:

   * Select **Create**.

   .. image:: static/12.4diyP28.png
      :alt: Create file system interface showing Create button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File System** interface:

   * See the successful file system initialization.

   .. image:: static/12.4diyP29.png
      :alt: File System interface showing successful creation notification.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **File System** interface:

   * Select **PetModels-EFS-1**.

   .. image:: static/12.4diyP30.png
      :alt: File System interface showing PetModels-EFS-1 selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-EFS-1** interface:

   * Select **Attach**.

   .. image:: static/12.4diyP31.png
      :alt: PetModels-EFS-1 interface showing Attach button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Attach** interface:

   * Copy **EFS mount helper** command line.

   .. image:: static/12.4diyP32.png
      :alt: Attach interface showing EFS mount helper command to copy.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Attach** interface:

   * Select **Close**.

   .. image:: static/12.4diyP33.png
      :alt: Attach interface showing Close button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/12.4diyP34.png
      :alt: AWS Console showing EC2 service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * View instances.

   .. image:: static/12.4diyP35.png
      :alt: EC2 interface showing Instances list.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Instances** interface:

   * Select **PetModels-A**.
   * Select **Connect**.

   .. image:: static/12.4diyP36.png
      :alt: EC2 Instances list showing PetModels-A selected and Connect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **Connect to instance** interface:

   * Select **EC2 Instance Connect**.
   * Select **Connect**.

   .. image:: static/12.4diyP37.png
      :alt: Connect to instance interface showing EC2 Instance Connect selected and Connect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Type ``sudo yum install -y amazon-efs-utils``.

   .. image:: static/12.4diyP38.png
      :alt: PetModels-A CLI showing yum install command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Enter ``mkdir data``.

   .. image:: static/12.4diyP39.png
      :alt: PetModels-A CLI showing mkdir command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Enter ``ls``.

   .. image:: static/12.4diyP40.png
      :alt: PetModels-A CLI showing ls command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Enter the command line of **Using the EFS mount helper** copied in step 32, and change ``efs`` to ``data``.

   .. image:: static/12.4diyP41.png
      :alt: PetModels-A CLI showing EFS mount command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Enter ``cd data``.

   .. image:: static/12.4diyP42.png
      :alt: PetModels-A CLI showing cd command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Type ``cat efs-l-setup.log``.

   .. image:: static/12.4diyP43.png
      :alt: PetModels-A CLI showing cat command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Type ``sudo bash -c "cat >> efs-l-setup.log"``.

   .. image:: static/12.4diyP44.png
      :alt: PetModels-A CLI showing sudo cat command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Enter ``efs-1-mounted in site B``.

   .. image:: static/12.4diyP45.png
      :alt: PetModels-A CLI showing text input for log file.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Use **Ctrl + C**.

   .. image:: static/12.4diyP46.png
      :alt: PetModels-A CLI showing Ctrl+C command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * Type ``cat efs-l-setup.log``.

   .. image:: static/12.4diyP47.png
      :alt: PetModels-A CLI showing cat log file command.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **PetModels-A** interface (CLI):

   * View results.

   .. image:: static/12.4diyP48.png
      :alt: PetModels-A CLI showing cat log file results.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface: {# Correcting "In delivery DIY" #}

   * Paste **Amazon EFS File System id** into **VALIDATION FORM**.
   * Select **VALIDATE**.

   .. image:: static/12.4diyP49.png
      :alt: DIY interface showing EFS File System ID pasted and Validate button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface: {# Ignoring "48. In the DIY interface" prefix #}

   * After selecting **VALIDATE**, **VALIDATION MESSAGE** appears **Success…**.
   * Select **EXIT**.

   .. image:: static/12.4diyP50.png
      :alt: DIY interface showing validation success message and Exit button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}

#. Select **COLLECT**. 

   .. image:: static/12.4diyP51.png
      :alt: City interface showing Collect button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/9-storage/9.4-diy/ {# Replace with actual URL #}
