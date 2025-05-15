  .. _a7_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **DIY** interface:

   * Read **DIY ACTIVITIES**.
   * Read **SOLUTION VALIDATION METHOD**.

   .. image:: static/A7D1.png
      :alt: DIY interface showing activities and validation method instructions.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **RDS**.
   * Select **RDS**.

   .. image:: static/A7D2.png
      :alt: AWS console showing RDS service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Amazon RDS** interface:

   * Select **Databases**.

   .. image:: static/A7D3.png
      :alt: RDS dashboard showing Databases option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Databases** interface:

   * Select **my-database**.

   .. image:: static/A7D4.png
      :alt: RDS database list showing my-database selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Databases** interface:

   * Select **Actions**.
   * Select **Create read replica**.

   .. image:: static/A7D5.png
      :alt: RDS database actions menu showing Create read replica option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Create read replica DB instance** interface:

   * In **DB instance class**, select **db.t3.xlarge-4 vCPU**.

   .. image:: static/A7D6.png
      :alt: Create read replica interface showing DB instance class selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Create read replica DB instance** interface:

   * In **Multi-AZ deployment**, select **Yes**.

   .. image:: static/A7D7.png
      :alt: Create read replica interface showing Multi-AZ selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Create read replica DB instance** interface:

   * In **Storage type**, select **General Purpose (SSD)**.

   .. image:: static/A7D8.png
      :alt: Create read replica interface showing Storage type selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Network & Security** interface:

   * In **Destination region**, select **US East (N. Virginia)**.

   .. image:: static/A7D9.png
      :alt: Create read replica interface showing Destination region selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Network & Security** interface:

   * In **Destination DB subnet group**, select **default-vpc**.

   .. image:: static/A7D10.png
      :alt: Create read replica interface showing Destination DB subnet group selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Network & Security** interface:

   * In **Publicly accessible**, select **No**.

   .. image:: static/A7D11.png
      :alt: Create read replica interface showing Publicly accessible setting.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Network & Security** interface:

   * In **VPC security groups**, select **default**.

   .. image:: static/A7D12.png
      :alt: Create read replica interface showing VPC security groups selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **RDS** interface (Create read replica):

   * In **Read replica source**, the source database ``my-database`` should be pre-filled.
   * In **DB instance identifier**, enter ``my-database-read-replica``.

   .. image:: static/A7D13.png
      :alt: Create read replica interface showing source and identifier fields.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **Database options** interface (Create read replica):

   * In **Database port**, enter ``3306``.
   * Select **Copy tags to snapshots**.

   .. image:: static/A7D14.png
      :alt: Create read replica interface showing database port and copy tags option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}

#. In the **RDS** interface (Create read replica):

   * In **Monitoring**, uncheck **Disable enhanced monitoring**.
   * In **Performance Insights**, uncheck **Disable Performance Insights**.
   * In **Maintenance**, select **No**.
   * Select **Create read replica**.

   .. image:: static/A7D15.png
      :alt: Create read replica interface showing monitoring, PI, maintenance settings, and create button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/7-database/7.4-diy/ {# Replace with actual URL #}
