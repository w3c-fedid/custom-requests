# Custom Requests

This is a [Stage 1](https://github.com/w3c-fedid/Administration/blob/main/proposals-CG-WG.md#stage-1) proposal of the [FedID CG](https://fedidcg.github.io/) to extend FedCM to allow RPs to make custom requests to the IdP.

# Champions

* @cbiesinger 

# Participate
- https://github.com/w3c-fedid/[your-proposal]/issues

# The Problem

FedCM’s account chooser and disclosure dialog only allows asking for permission to share standard claims (e.g. user’s name, email address and profile picture). However, commonly Identity Providers (IdPs) need to ask for additional information before returning the token to the relying party (RP), such as requesting re-authentication, scopes beyond standard claims (e.g. API access), verifying up-to-date contact information, parental controls, etc.

There is currently no mechanism that an IdP can use to use their own words to request their user's permission before returning a token to the RP.

# The Proposal

The proposal is to introduce:

1. The API affordance that allow RPs to pass [custom requests](https://github.com/w3c-fedid/continuation/issues/2) to IdPs
1. The API affordance that allows IdPs to [continue and finish](https://github.com/w3c-fedid/continuation/issues/1) the request in a popup window
1. The API affordance that allow RPs to [select](https://github.com/w3c-fedid/continuation/issues/4) which attributes of the user's profile they are looking for

# Alternatives Considered

# Acknowledgements
