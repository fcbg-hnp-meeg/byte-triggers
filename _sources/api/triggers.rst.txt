Triggers
--------

.. currentmodule:: byte_triggers

.. autosummary::
    :toctree: ../generated/api/

    LSLTrigger
    MockTrigger
    ParallelPortTrigger

All trigger classes have a ``.signal()`` method used to deliver an integer trigger. The
typical usage is:

.. code-block:: python

    from byte_triggers import MockTrigger

    trigger = MockTrigger()
    trigger.signal(1)
