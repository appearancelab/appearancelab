---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}
## Principal Investigator
{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

## Researchers and Students
{% include list.html data="members" component="portrait" filter="role != 'pi' and role != 'collaborator'" %}

## Current Collaborators
Empty for now
## Past Collaborators
Empty for now
