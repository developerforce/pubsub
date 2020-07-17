# The c/pubsub cross DOM messaging component

This is repo contains the source for the `c/pubsub` component that was made available when Lightning Web Components (LWC) were launched in early 2019. This component was a temporary solution for lack of feature-parity between LWC and Aura components related to cross-DOM messaging. 

The Aura components `<aura:event>` feature allowed for messaging between components across a complex DOM tree structure. 

`c/pubsub` served to implement an analogous feature that would work for LWC and Aura components. 

As of July 2020, `c/pubsub` has been superseded by the [Lightning Message Service][1]. For this reason it has been retired from our [sample apps][2]. 

However, as there are still some [limitations][3] with Lightning Message Service, we've kept the core components involved in using `c/pubsub` available in this repo for use by Salesforce developers. 

Please remember that `c/pubsub` falls under no support agreement with Salesforce.

[1]: https://developer.salesforce.com/docs/component-library/documentation/en/lwc/lwc.use_message_channel
[2]: https://trailhead.salesforce.com/sample-gallery
[3]: https://developer.salesforce.com/docs/component-library/documentation/en/lwc/lwc.use_message_channel_considerations