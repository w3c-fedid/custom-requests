# Your Proposal

This is a [Proposal](https://fedidcg.github.io/charter#proposals) of the [Federated Identity Community Group](https://fedidcg.github.io/) to extend FedCM to allow RPs to make custom requests to the IdP.

# Stage

This is a [Stage 1](https://github.com/w3c-fedid/Administration/blob/main/proposals-CG-WG.md#stage-1) proposal.

# Champions

* @cbiesinger 

# Participate
- https://github.com/w3c-fedid/[your-proposal]/issues

# The Problem

FedCM’s account chooser and disclosure dialog only allows asking for permission to share standard claims (e.g. user’s name, email address and profile picture). However, commonly Identity Providers (IdPs) need to ask for additional information before returning the token to the relying party (RP), such as requesting re-authentication, scopes beyond standard claims (e.g. API access), verifying up-to-date contact information, parental controls, etc.

There is currently no mechanism that an IdP can use to use their own words to request their user's permission before returning a token to the RP.

# The Proposal

The proposal is to:

1. Allow IdPs to [continue](https://github.com/w3c-fedid/continuation/issues/1) and finish the request in a popup window
2. Allow RPs to [select](https://github.com/w3c-fedid/continuation/issues/4) which attributes of the user's profile they are looking for and
3. Allow RPs to pass a [custom request](https://github.com/w3c-fedid/continuation/issues/2) to IdPs

# Alternatives Considered

# Acknowledgements
