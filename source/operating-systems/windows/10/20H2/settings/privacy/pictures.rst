.. _w10-20h2-settings-privacy-pictures:

Pictures
########
:cmdmenu:`⌘ + r --> ms-settings:privacy-pictures`

See :ref:`w10-determining-app-list` to generate a list of apps for more fine
grained control of app access.

Allow access to picture libraries on this device
************************************************
.. dropdown:: Enable Allow access to picture libraries on this device
  :container: + shadow
  :title: bg-primary text-white font-weight-bold
  :animate: fade-in

  Do not configure or leave enabled. Can restrict picture folder access from all
  apps and Windows. There is no GPO equivalent.

  .. dropdown:: :term:`Registry`
    :title: font-weight-bold
    :animate: fade-in
    :open:

    ``Deny`` will disable all access.

    .. wregedit:: Enable Allow access to picture libraries on this device
      :key_title: HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\
                  CapabilityAccessManager\ConsentStore\picturesLibrary
      :names:     Value
      :types:     SZ
      :data:      Allow
      :no_section:
      :no_caption:
  
  `Reference <https://www.tenforums.com/tutorials/102590-allow-deny-os-apps-access-pictures-library-windows-10-a.html>`__

Allow app access to picture libraries on this device
****************************************************
.. dropdown:: Enable Allow app access to picture libraries on this device
  :container: + shadow
  :title: bg-primary text-white font-weight-bold
  :animate: fade-in

  Do not configure or leave enabled. Can restrict picture folder access from all
  apps and Windows. There is no GPO equivalent.

  .. dropdown:: :term:`Registry`
    :title: font-weight-bold
    :animate: fade-in
    :open:

    .. wregedit:: Enable Allow app access to picture libraries on this device
      :key_title: HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\
                  CapabilityAccessManager\ConsentStore\picturesLibrary
      :names:     Value
      :types:     SZ
      :data:      Allow
      :no_section:
      :no_caption:

  `Reference <https://www.tenforums.com/tutorials/102590-allow-deny-os-apps-access-pictures-library-windows-10-a.html>`__

Choose which apps can access your pictures library
**************************************************
See :ref:`w10-20h2-settings-privacy-pictures`.
