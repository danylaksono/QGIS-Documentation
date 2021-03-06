.. |updatedisclaimer|

.. comment out this Section (by putting '|updatedisclaimer|' on top) if file is not uptodate with release

.. index:: SPIT, Shapefile_to_Postgis_Import_Tool

.. _label_spit:

SPIT Plugin
===========

|qg| comes with a plugin named SPIT (Shapefile to PostGIS Import Tool). SPIT can
be used to load multiple shapefiles at one time and includes support for schemas.
To use SPIT, open the Plugin Manager from the :menuselection:`Plugins` menu,
in the |plugin| :guilabel:`Installed` menu check the box next to the |checkbox| :guilabel:`SPIT plugin`
and click **[OK]**. The SPIT icon will be added to the plugin toolbar.

To import a shapefile, click on the |spiticon| :sup:`SPIT` tool in the toolbar
to open the :guilabel:`SPIT - Shapefile to PostGIS Import Tool` dialog. Select
the PostGIS database you want to connect to and click on **[Connect]**. If you
want, you can define or change some import options. Now you can add one or more
files to the queue by clicking on the **[Add]** button. To process the files,
click on the **[OK]** button. The progress of the import as well as any
errors/warnings will be displayed as each shapefile is processed.

.. _figure_spit_1:

.. only:: html

   **Figure SPIT Plugin 1:**

.. figure:: /static/user_manual/plugins/spit_plugin.png
   :width: 30em
   :align: center

   Using SPIT Plugin to import Shape files to PostGIS |nix|

.. _tip_importing_shapefiles:
