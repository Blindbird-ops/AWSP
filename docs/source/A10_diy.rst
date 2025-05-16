  .. _a10_diy:

===
DIY
===

After completing the lab, the player does DIY.

#. In the **AWS Console** interface:

   * Find **Amazon DynamoDB**.
   * Select **Amazon DynamoDB**.

   .. image:: static/13.4diyP01.png
      :alt: AWS Console showing Amazon DynamoDB service.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **DynamoDB** interface:

   * Select **Update settings**. {# Keeping "Update settings" as provided in source text #}
   * Select **UserVideoHistory** (table).
   * Select **Actions**.
   * Select **Create item**.

   .. image:: static/13.4diyP02.png
      :alt: DynamoDB interface navigating to create an item for UserVideoHistory.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * In **userId**, enter ``12345-abcd-6785``.

   .. image:: static/13.4diyP03.png
      :alt: Create item interface showing userId entry.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * In **lastDateWatched**, enter ``1619156407``.

   .. image:: static/13.4diyP04.png
      :alt: Create item interface showing lastDateWatched entry.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * Select **Add new attribute**.

   .. image:: static/13.4diyP05.png
      :alt: Create item interface showing Add new attribute button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * Select **Number** (for the new attribute type).

   .. image:: static/13.4diyP06.png
      :alt: Create item interface showing Number attribute type selected.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * For **Attribute name**, enter ``Rating``.
   * (Note: This should be lowercase ``rating`` for validation).

   .. image:: static/13.4diyP07.png
      :alt: Create item interface showing Rating attribute name entry.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * For **Value**, enter ``5``.

   .. image:: static/13.4diyP08.png
      :alt: Create item interface showing Rating attribute value entry.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Create item** interface:

   * Select **Create item**.

   .. image:: static/13.4diyP09.png
      :alt: Create item interface showing Create item button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **DynamoDB** interface:

   * View **Items returned** (should show the new item).

   .. image:: static/13.4diyP10.png
      :alt: DynamoDB interface showing items returned with the new item.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Item editor** interface:

   * In **Attribute name** column, edit "Rating" to ``rating``. {# Correcting the attribute name #}

   .. image:: static/13.4diyP11.png
      :alt: Item editor interface showing attribute name being edited to lowercase rating.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **Item editor** interface:

   * Select **Save changes**.

   .. image:: static/13.4diyP12.png
      :alt: Item editor interface showing Save changes button.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}

#. In the **DIY** interface:

   * Enter **UserVideoHistory** into **DynamoDB table name** field.
   * Enter **12345-abcd-6785** in **Item User Id** field.
   * Select **VALIDATE**.

   .. image:: static/13.4diyP13.png
      :alt: DIY interface showing table name and user ID entered for validation.
      :align: center
      :width: 600px
      :target: https://000300.awsstudygroup.com/10-databases/10.4-diy/ {# Replace with actual URL #}
