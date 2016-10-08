# Privoxy Generic Filters
This is general-purpose filter for privoxy.
## How to use
You add **"actionsfile generic.action"** to config.
> actionsfile match-all.action # Actions that are applied to all sites and maybe overruled later on.  
> actionsfile default.action   # Main actions file  
> **actionsfile generic.action**  
> actionsfile user.action      # User customizations

You add **"filtersfile generic.filter"** to config.
> filterfile default.filter  
> **filterfile generic.filter**  
> filterfile user.filter      # User customizations
