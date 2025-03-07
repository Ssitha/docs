.. _w10-21h2-settings-privacy-motion:

Motion
######
:cmdmenu:`⌘ + r --> ms-settings:privacy-motion`

.. note::
  Only displayed in GUI if motion detection device is present (e.g. phone,
  pedometer, etc.).

Let Windows and your apps use your motion data and collect motion history
*************************************************************************
.. dropdown:: Disable Let Windows and your apps use your motion data and collect
              motion history
  :container: + shadow
  :title: bg-primary text-white font-weight-bold
  :animate: fade-in
  :open:

  Disable access to motion data.

  .. gpo::    Disable apps use your motion data and collect motion history
    :path:    Computer Configuration -->
              Administrative Templates -->
              Windows Components -->
              App Privacy -->
              Let Windows apps access motion
    :value0:  ☑, {ENABLED}
    :value1:  Default for all apps, Force Deny
    :ref:     https://docs.microsoft.com/en-us/windows/privacy/manage-connections-from-windows-operating-system-components-to-microsoft-services#1818-motion
    :update:  2021-02-19
    :generic:
    :open:

  .. gpo::    Disable apps use your motion data and collect motion history
    :path:    Computer Configuration -->
              Administrative Templates -->
              Windows Components -->
              App Privacy -->
              Let Windows apps access user movements while running in the background
    :value0:  ☑, {ENABLED}
    :value1:  Default for all apps, Force Deny
    :ref:     https://docs.microsoft.com/en-us/windows/privacy/manage-connections-from-windows-operating-system-components-to-microsoft-services#1818-motion
    :update:  2021-02-19
    :generic:
    :open:
