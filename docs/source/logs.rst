Latest Logs From Latest Build
==============================

Generated On: 2024-11-07 18:26:09 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Defendx3/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-07_18:24:21] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-07_18:24:24] STEP 2: Create topics started

  [INFO 2024-11-07_18:25:10] STEP 2: Completed

  [INFO 2024-11-07_18:25:16] STEP 3: producing data started

  [ERROR 2024-11-07_18:25:18] Cannot connect to MQTT broker in tml_read_MQTT_step_3_kafka_producetotopic_dag-dateNov07H-f2d7.py - invalid literal for int() with base 10: ''

  [INFO 2024-11-07_18:25:19] STEP 4: Preprocessing started

  [INFO 2024-11-07_18:25:21] STEP 4: Preprocessing started

  [INFO 2024-11-07_18:25:22] STEP 7: Visualization started

  [INFO 2024-11-07_18:25:28] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-07_18:25:35] STEP 8: Starting docker push for: defendx/dateNov07H-f2d7-amd64

  [WARN 2024-11-07_18:25:55] STEP 8: There seems to be an issue creating the container.  Here is the commit command: docker commit c957405403d0 defendx/dateNov07H-f2d7-amd64 - message=1.  Container may NOT pushed.

  [WARN 2024-11-07_18:26:02] STEP 8: There seems to an issue pushing to Docker.  Here is the command: docker push defendx/dateNov07H-f2d7-amd64 - message=1

  [INFO 2024-11-07_18:26:08] STEP 10: Started to build the documentation

  [INFO 2024-11-07_18:26:09] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


