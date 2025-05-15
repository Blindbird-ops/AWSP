.. _a8_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **AWS Console** interface:

   * Find **IAM**.
   * Select **IAM**.

   .. image:: static/A8D1.png
      :alt: AWS console showing IAM service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface:

   * Select **User groups**.
   * Select the **SupportEngineers** group.
   * Select **Permissions**.

   .. image:: static/A8D2.png
      :alt: IAM user groups interface showing SupportEngineers selected and Permissions tab.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface (Permissions):

   * Find **AmazonEC2ReadOnlyAccess** (policy attached to the group).
   * Select **AmazonEC2ReadOnlyAccess**.

   .. image:: static/A8D3.png
      :alt: IAM group permissions showing AmazonEC2ReadOnlyAccess policy found and selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface (Permissions):

   * Select **Add permissions**.

   .. image:: static/A8D4.png
      :alt: IAM group permissions interface showing Add permissions button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **Add permissions** interface:

   * In **Add permissions**, select **Attach policies**.

   .. image:: static/A8D5.png
      :alt: IAM Add permissions interface showing Attach policies option.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface (Attach policies):

   * Find **RDSReadOnlyAccess**.
   * Select **AmazonRDSReadOnlyAccess**.

   .. image:: static/A8D6.png
      :alt: IAM Attach policies interface showing search for and selection of RDSReadOnlyAccess.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface (Attach policies):

   * Select **Add permissions** (to attach the selected policy).

   .. image:: static/A8D7.png
      :alt: IAM Attach policies interface showing Add permissions button to finalize attachment.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **IAM** interface:

   * Select **User groups**.
   * Select **Permissions**.
   * View the **Policy name** list (should now include RDSReadOnlyAccess).

   .. image:: static/A8D8.png
      :alt: IAM user groups interface showing Permissions tab with updated policy list.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface:

   * Enter **SupportEngineers** (user group name).
   * Select **VALIDATE**.

   .. image:: static/A8D9.png
      :alt: DIY interface showing user group name entry and Validate button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface:

   * After selecting **VALIDATE**, **VALIDATION MESSAGE** appears.
   * View the message “**You have granted the correct permissions…**”.
   * Select **EXIT** to exit.

   .. image:: static/A8D10.png
      :alt: DIY interface showing validation success message.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}

#. After returning to the city interface:

   * Select **ASSIGNMENT**.
   * Select **COLLECT**.
   * Select **NEXT**.
   * Select **COLLECT**.
   * Congratulations to the award winning player!

   .. image:: static/A8D11.png
      :alt: City interface showing assignment collection and final congratulations.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/8-security/8.4-diy/ {# Replace with actual URL #}
