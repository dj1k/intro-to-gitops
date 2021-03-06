---
title: "At an AWS Event"
chapter: false
weight: 10
---

{{% notice warning %}}
Only complete this section if you are at an AWS hosted event (such as re:Invent,
Kubecon, Immersion Day, or any other event hosted by an AWS employee). If you are running the workshop on your own, goto: [Start the workshop on your own](/10_aws_prerequisites/20_self_paced.html).
{{% /notice %}}

### Login to AWS Workshop Portal

This workshop creates an AWS account, EKS Cluster, ELB and Route 53 environments that will be managed by eksctl. You will need the **Participant Hash** provided upon entry, and your email address to track your unique session.

Connect to the portal by clicking the button or browsing to [https://dashboard.eventengine.run/](https://dashboard.eventengine.run/). The following screen shows up.

![Event Engine](/images/event-engine-initial-screen.png)

Enter the provided hash in the text box. The button on the bottom right corner changes to **Accept Terms & Login**. Click on that button to continue.

![Event Engine Dashboard](/images/event-engine-dashboard.png)

Click on **AWS Console** on dashboard.

![Event Engine AWS Console](/images/event-engine-aws-console.png)

Take the defaults and click on **Open AWS Console**. This will open AWS Console in a new browser tab.

### Next step

Once you have completed the step above, you can leave the AWS console open. You can now move to the [**ekstctl Setup**](/20_eksctl_prerequisites.html) section. 
