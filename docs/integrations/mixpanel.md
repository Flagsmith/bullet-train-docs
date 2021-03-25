description: Integrate Flagsmith with Mixpanel

# Mixpanel Analytics Integration

<img src="/images/integrations/mixpanel/mixpanel-logo.svg"/>

!!! note
    This feature is currently in beta. Please contact us if you are interested in joining the beta!

You can integrate Flagsmith with Mixpanel. The integration automatically sends the flag states for identified users into Mixpanel for cohort analysis, A/B testing and more. The process is as follows:

## Integration Setup

1. Get the Mixpanel Project Environment ID for your Mixpanel project from the Mixpanel Manage Project page (Project Settings > Project Token)
2. Add the Project Token into Flagsmith (Integrations > Add Mixpanel Integration)
3. All API calls generated by the Flagsmith SDK to the `Get Identity Flags` endpoint will send the a full set of flag evaluations for that particular user to Mixpanel as a [`User Profile`](https://developer.mixpanel.com/reference/user-profiles)

## Use Case

Once the integration has been set up, you can start segmenting your Mixpanel identities based on the flags that they saw. This means you can run AB tests driven by Flagsmith segments, and have the data show up automatically in Mixpanel.

## Integration Notes

You have to identify users on both platforms in the same way. The Flagsmith `Identity ID` must be the same as the Mixpanel `identity`.