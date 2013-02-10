An easy to use API for developing _World of Warcraft_ AddOns.

### Contributing

This API uses Jekyll to generate the site. If you'd like to contribute to function definitions, please use as much of this YAML metadata as needed.

```yaml
# You shouldn't change the layout.
layout: function

# The function name. No spaces.
title:

# The category of function (e.g., "Account", "Merchant", "Combat", et cetera)
category:

# Describe what the function does in a single line.
description: 

# A list of arguments the function takes.
arguments:
  # The name of the argument
- name:
  # The type of the argument
  type:
  # A brief description of the argument
  description:

# A list of values the function returns.
returns:
  # The name of the value
- name:
  # The type of the value
  type:
  # A brief description of the value
  description:

# A list of events the function throws.
events:
```