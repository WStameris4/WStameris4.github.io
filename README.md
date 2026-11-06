# WStameris4.github.io

Hosts the public key for my Tesla Fleet API application, which Home Assistant's
[Tesla Fleet integration](https://www.home-assistant.io/integrations/tesla_fleet) uses to sign
vehicle commands.

Tesla fetches it from:

    https://wstameris4.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

This is a **public** key; the matching private key never leaves Home Assistant.
`.nojekyll` makes GitHub Pages publish the `.well-known` directory, which Jekyll would otherwise skip.
