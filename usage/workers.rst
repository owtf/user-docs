Managing Workers
================

Workers are the actual processes that run the plugins. Control over these worker processes
is provided from worker manager page.

    .. figure:: /images/worker_manager_active.png
        :align: center

There are three main controls in worker manager:

Pausing/Resuming Workers
------------------------

You can **pause/resume** any worker separately. We care a lot about your time. Is your internet connection down or
Is any target not responding & your web vulnerability scanner plugin is halfway through? Don't worry, we got your back.
All you have to do is pause the worker and resume it when the target is back up. Isn't this l33t?

    .. figure:: /images/worker_manager_inactive.png
        :align: center

Abort Workers
-------------

You can **abort** any worker. If you wish to abort any plugin during execution, just click on the red cross. Do the same if you
wish to remove an extra idle worker.

Add Workers
-----------

You can **add new workers** on the fly if you have many targets and running many plugins simultaneously

    .. warning::
        Maximum of one plugin per target will be running at any moment of time

    .. figure:: /images/worker_manager_multiple_active.png
        :align: center
