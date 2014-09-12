Controlling Worklist
====================

work
    Any plugin when launched against a target, adds a (plugin, target) combination to the worklist. This
    combination is known as work

worklist
    The list consisting of all works which are yet to be assigned to a worker

Worklist can be managed from worklist manager which looks like this

    .. figure:: /images/worklist_manager_running.png
        :align: center

Worklist table provides interesting information like:

    * Estimated time for which plugin will run
    * All details about the plugin and the target against which it is launched

Pausing Work
------------

Individual works or whole worklist can be paused. This will stop the work from getting assigned to any worker.
The interesting part is ``worklist is persistent``. If you pause the whole worklist and exit OWTF, the next time
you start OWTF the works will still be there in paused state

    .. figure:: /images/worklist_manager_mixed.png
        :align: center

Deleting Work
-------------

Any work can be delete from the worklist. The search boxes will help in filtering of works when there are many
entries
