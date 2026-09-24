# Collector Package
## What is this?
Add a collector system to your ballsdex bot! Supports multiple rewards and multiple specials, fully customizable both through discord commands (slash and flag commands) and in the admin panel!
## Commands
* /collector list : shows all available collector balls
* /collector claim : shows which balls are ready to claim and progress on specific requirements
## Admin commands 
* /admin collector set : Set a requirement for a ball
* /admin collector delete : Delete all collector requirements from a ball or a specific special requirement
* /admin collector view : View collector requirements of a specific ball
* /admin collector bulk : Add easily multiple requirements for multiple balls with multiple special rewards
Every single admin command is available as a flag command (b.admin collector .. )
## How to install
Add this to config/extra.toml (or create the file if it doesn't exist)
```toml
# Collector Package
[[ballsdex.packages]]
location = "git+https://github.com/GlitchedGlitch/BallsDex-Collector-Package.git@1.0.0"
path = "collector"
enabled = true
```
