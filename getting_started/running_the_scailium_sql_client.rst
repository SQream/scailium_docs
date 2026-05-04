.. _running_the_scailium_sql_client:

*****************************
Running the SCAILIUM SQL Client
*****************************

The following example shows how to run the SCAILIUM SQL client:

.. code-block:: psql

   $ sqream sql --port=5000 --username=rhendricks -d master
   Password:
   
   Interactive client mode
   To quit, use ^D or \q.
  

Running the SCAILIUM SQL client prompts you to provide your password. Use the username and password that you have set up, or your DBA has provided.
  
.. tip::
   * You can exit the shell by typing ``\q``  or :kbd:`Ctrl-d`. 
   * A new SCAILIUM cluster contains a database named `master,` which is the database used in the examples on this page.