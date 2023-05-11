Create autostart:

set_autostart_registry('App name', r'C:\test\x.exe')

Update autostart:

set_autostart_registry('App name', r'C:\test\y.exe')

Delete autostart:

set_autostart_registry('App name', autostart=False)

Check autostart:

if check_autostart_registry('App name'):
