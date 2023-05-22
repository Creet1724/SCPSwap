# SCPSwap

### How do I download this?
  - Go here and download the latest release, https://github.com/Creet1724/SCPSwap/releases

### Default Config
```yml
ScpSwap:
  is_enabled: true
  # Indicates whether debug messages should be shown.
  debug: false
  # The duration, in seconds, before a swap request gets automatically deleted.
  request_timeout: 20
  # The duration, in seconds, after the round starts that swap requests can be sent.
  swap_timeout: 60
  # Indicates whether a player can switch to a class if there is nobody playing as it.
  allow_new_scps: true
  # A collection of roles blacklisted from being swapped to.
  blacklisted_scps:
  - Scp0492
  # Allows/Disallows SCP-049-2 from swapping to other SCPs.
  zombie_swapping: false
  # Allows/Disallows SCP-049-2 from swapping to other SCPs.
  zombie_swapping_disallow_message: So, you are a zombie, you can't swap with another SCP. (fixed by Creet1724)
  # A collection of the names of custom scps blacklisted from being swapped to. This must match the name the developer integrated the SCP into this plugin's API with.
  blacklisted_names: []
```
