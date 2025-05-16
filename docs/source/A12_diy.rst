.. _a12_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **DIY** interface:

   * Read **DIY ACTIVITIES**. {# Correcting typo "ACCTIVITIES" #}
   * Read **SOLUTION VALIDATION METHOD**.

   .. image:: static/15.4diyP1.png
      :alt: DIY interface showing instructions.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface:

   * Select **START LAB**.

   .. image:: static/15.4diyP2.png
      :alt: DIY interface showing Start Lab button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **AWS Console** interface:

   * Find **EC2**.
   * Select **EC2**.

   .. image:: static/15.4diyP3.png
      :alt: AWS Console showing EC2 service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Instances**.
   * Select **lab/TravelAgencyWebServers** (the instance).
   * Select **Details** to view instance details.

   .. image:: static/15.4diyP4.png
      :alt: EC2 interface navigating to view instance details.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Auto Scaling Groups**.
   * Select **TravelAgencyWebServers** auto scaling group.
   * Select **Details** to see the details of the auto scaling group.

   .. image:: static/15.4diyP5.png
      :alt: EC2 interface navigating to view ASG details.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Auto Scaling Groups**.
   * Select **TravelAgencyWebServers** Auto Scaling Group.
   * Select **Instance management**.
   * View instance information.

   .. image:: static/15.4diyP6.png
      :alt: EC2 interface navigating to view ASG instances.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Auto Scaling Groups**.
   * Select **TravelAgencyWebServers**.
   * Select **Details** to view **Desired capacity**, **Minimum capacity**, **Maximum capacity**.

   .. image:: static/15.4diyP7.png
      :alt: EC2 interface showing ASG capacity details.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Auto Scaling Groups**.
   * Select **TravelAgencyWebServers** Auto Scaling Group.
   * In **Network**, see **Subnet ID** information.
   * In **Load balancing**, select **Edit**.

   .. image:: static/15.4diyP8.png
      :alt: EC2 interface viewing ASG network info and selecting edit load balancing.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit TravelAgencyWebServers** interface: {# Correcting typo "TravleAgency" #}

   * Select **Add a new load balancer**.

   .. image:: static/15.4diyP9.png
      :alt: Edit ASG interface showing Add a new load balancer option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Load balancing** interface:

   * For **Load balancer type**, select **Application Load Balancer**.
   * For **Load balancer scheme**, select **Internet-facing**.

   .. image:: static/15.4diyP10.png
      :alt: Load balancing interface showing ALB type and scheme selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the interface **Edit TravelAgencyWebServers**: {# Correcting typo "TravleAgency" #}

   * In **Availability Zones and subnets**, select all 3 **AZ** and subnets. {# Correcting typo "AZ*" #}

   .. image:: static/15.4diyP11.png
      :alt: Edit ASG interface showing AZ and subnet selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the interface **Edit TravelAgencyWebServers**:

   * In **Default routing (forward to)**, select **Create a target group**.

   .. image:: static/15.4diyP12.png
      :alt: Edit ASG interface showing Create a target group option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the interface **Edit TravelAgencyWebServers**:

   * Select **Update**.

   .. image:: static/15.4diyP13.png
      :alt: Edit ASG interface showing Update button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Auto Scaling Groups** interface:

   * View update results.

   .. image:: static/15.4diyP14.png
      :alt: Auto Scaling Groups interface showing update results.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Auto Scaling Groups** interface:

   * Select **TravelAgencyWebServers** Auto Scaling Group (from the list).

   .. image:: static/15.4diyP15.png
      :alt: Auto Scaling Groups interface showing ASG selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Auto Scaling Groups** interface:

   * Select **Details** to see details.

   .. image:: static/15.4diyP16.png
      :alt: Auto Scaling Groups interface showing Details link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Security Groups**.

   .. image:: static/15.4diyP17.png
      :alt: EC2 interface showing Security Groups link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Security Groups** interface: {# Clarifying interface #}

   * Select **Create security group**.

   .. image:: static/15.4diyP18.png
      :alt: EC2 Security Groups interface showing Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * For **Security group name**, enter ``TravelAgencyLoadBalancer``.

   .. image:: static/15.4diyP19.png
      :alt: Create security group interface showing name field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * In **Description**, enter ``Allow access to the Travel Agency Load Balancer from the Internet``. {# Correcting typo "Decription" #}

   .. image:: static/15.4diyP20.png
      :alt: Create security group interface showing description field.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * In **VPC**, select **lab/TravelAgencyVpc**.

   .. image:: static/15.4diyP21.png
      :alt: Create security group interface showing VPC selection.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create security group** interface:

   * Select **Add rule** (Inbound).

   .. image:: static/15.4diyP22.png
      :alt: Create security group interface showing Add rule button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create Security group** interface (Rules):

   * In **Inbound rules**, select **HTTP**.

   .. image:: static/15.4diyP23.png
      :alt: Create security group inbound rules showing HTTP type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create Security group** interface (Rules):

   * In **Outbound rules**, select **HTTP**. {# Correcting typo "Oubound" #}

   .. image:: static/15.4diyP24.png
      :alt: Create security group outbound rules showing HTTP type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Create Security group** interface:

   * Select **Create security group**.

   .. image:: static/15.4diyP25.png
      :alt: Create security group interface showing Create security group button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Security Groups**.

   .. image:: static/15.4diyP26.png
      :alt: EC2 interface showing Security Groups link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Security Groups** interface:

   * Select **TravelAgencyWebServer** security group. {# Correcting typo "security group*" #}

   .. image:: static/15.4diyP27.png
      :alt: EC2 Security Groups interface showing TravelAgencyWebServer security group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Security Groups** interface:

   * Select **Actions**.

   .. image:: static/15.4diyP28.png
      :alt: EC2 Security Groups interface showing Actions menu.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Security Groups Actions** menu: {# Clarifying interface #}

   * Select **Edit inbound rules**. {# Correcting typo "inblound" #}

   .. image:: static/15.4diyP29.png
      :alt: Security Groups Actions menu showing Edit inbound rules option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit inbound rules** interface:

   * Select **Delete** (the existing rule).

   .. image:: static/15.4diyP30.png
      :alt: Edit inbound rules interface showing delete option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit inbound rules** interface:

   * Select **Add rule**.

   .. image:: static/15.4diyP31.png
      :alt: Edit inbound rules interface showing Add rule button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit Inbound rules** interface:

   * Select **HTTP**.

   .. image:: static/15.4diyP32.png
      :alt: Edit inbound rules interface showing HTTP type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit Inbound rules** interface:

   * For **Source**, select **Custom**, select **TravelAgencyLoadBalancer** (security group).

   .. image:: static/15.4diyP33.png
      :alt: Edit inbound rules interface showing source security group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit Inbound rules** interface:

   * Select **Save rules**. {# Correcting typo "Sae" #}

   .. image:: static/15.4diyP34.png
      :alt: Edit inbound rules interface showing Save rules button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface: {# Correcting typo "EC2’" #}

   * Select **Load Balancers**.

   .. image:: static/15.4diyP35.png
      :alt: EC2 interface showing Load Balancers link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Load Balancers** interface: {# Clarifying interface #}

   * Select **TravelAgencyWebServers-1** Load Balancer.

   .. image:: static/15.4diyP36.png
      :alt: EC2 Load Balancers interface showing ALB selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Load Balancer** interface:

   * Select **Description** to view description information.

   .. image:: static/15.4diyP37.png
      :alt: Load Balancer interface showing Description link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Load Balancer** interface:

   * Select **Edit security groups**.

   .. image:: static/15.4diyP38.png
      :alt: Load Balancer interface showing Edit security groups link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit security groups** interface: {# Clarifying interface #}

   * Select **TravelAgencyLoadBalancer** security group (to add).

   .. image:: static/15.4diyP39.png
      :alt: Edit security groups interface showing TravelAgencyLoadBalancer security group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Edit security groups** interface:

   * Uncheck **TravelAgencyWebServer** security group (to remove).

   .. image:: static/15.4diyP40.png
      :alt: Edit security groups interface showing TravelAgencyWebServer security group unchecked.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Load Balancers**.

   .. image:: static/15.4diyP41.png
      :alt: EC2 interface showing Load Balancers link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Load Balancers** interface:

   * Select **TravelAgencyWebServer-1** Load Balancer.

   .. image:: static/15.4diyP42.png
      :alt: EC2 Load Balancers interface showing ALB selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Load Balancer** interface:

   * In **Description**, view and copy **DNS name**.

   .. image:: static/15.4diyP43.png
      :alt: Load Balancer interface showing DNS name to copy.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. Open a browser.

   .. image:: static/15.4diyP44.png
      :alt: Web browser opened.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. Paste **DNS name** into the browser.

   .. image:: static/15.4diyP45.png
      :alt: Browser showing DNS name pasted.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. Select **Enter** and see the interface.

   .. image:: static/15.4diyP46.png
      :alt: Browser showing Enter key pressed.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the browser:

   * Follow the end of **DNS name**: ``/health``.

   .. image:: static/15.4diyP47.png
      :alt: Browser showing /health added to the DNS name.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the browser:

   * View results.

   .. image:: static/15.4diyP48.png
      :alt: Browser showing health check results.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2** interface:

   * Select **Target Groups**.

   .. image:: static/15.4diyP49.png
      :alt: EC2 interface showing Target Groups link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **EC2 Target Groups** interface: {# Clarifying interface #}

   * Select **TravelAgencyWebServers** target group.

   .. image:: static/15.4diyP50.png
      :alt: EC2 Target Groups interface showing target group selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Target Group** interface: {# Clarifying interface #}

   * Select **Health checks**.

   .. image:: static/15.4diyP51.png
      :alt: Target Group interface showing Health checks link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the interface **Edit health check settings**:

   * In **Health check path**, enter ``/health``.
   * Select **Advanced health check settings**.

   .. image:: static/15.4diyP52.png
      :alt: Edit health check settings interface showing path and advanced settings link.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **Advanced health check settings** interface:

   * In **Unhealthy threshold**, enter ``2``. {# Correcting typo "Unhealthly" #}
   * In **Timeout**, enter ``2``.
   * In **Interval**, enter ``5``.
   * Select **Save changes**.

   .. image:: static/15.4diyP53.png
      :alt: Advanced health check settings interface showing thresholds, timeout, interval, and save.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface: {# Grouping validation and exit #}

   * Paste **TravelAgencyWebServers-1** into **Your ALB name** field.
   * Paste **TravelAgencyWebServers** into **Your Auto Scaling group name** field. {# Correcting typo "TravelAgencyWebSersers" #}
   * Select **VALIDATE**.
   * In **VALIDATION MESSAGE** appears **Success! All 3 Availability Zones are covered by instances behind a Load Balancer**.
   * Select **EXIT** to return to the city interface.

   .. image:: static/15.4diyP54.png
      :alt: DIY interface showing validation input, success message, and exit.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. In the **city interface**: {# Grouping city collection steps #}

   * Select **ASSIGNMENTS**.
   * Select **COLLECT**.
   * Select **NEXT**.
   * Select **COLLECT**.

   .. image:: static/15.4diyP55.png
      :alt: City interface showing collection steps.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/12-high-availability/12.4-diy/ {# Replace with actual URL #}

#. **Congratulations to the player receiving the reward!** {# This is step 56, no image #}
