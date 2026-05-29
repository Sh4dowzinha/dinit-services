# Collection of my dinit services

### For any additional services, look up dinit on the artix repos, I will mainly maintain what's not there and some modifications of already existent services.



## Instructions

The repo structure is just like the /etc directory. Just copy the services you want to there.

## Important

Set up turnstile or dinit-user-spawn for user services to work (also needed for wireplumber, pipewire, dbus, etc.)

For tlp-pd to work, you have to copy the dbus-1 folder and its contents to /etc, as the tlp-pd service depends on it.
