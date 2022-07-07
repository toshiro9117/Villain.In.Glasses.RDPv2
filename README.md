## Description
**What is RDP?**<br>
* RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.

**How long does this RDP stay active?**<br>
* This RDP stays active for up to 6 hours.<br>

## How to use it?

#### First Step
1. Press the **fork** button  
2. Login or signup to ngrok: https://ngrok.com
3. Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
> You'll get token from here. It'll be needed to the next step.

#### Second Step
1. In your forked repo: **Go to Settings > Secrets > Action > New Repository Secret**
2. In the name section, enter this text: **NGROK_AUTH_TOKEN**
3. In the value section, enter the **ngrok token**
4. Then press **Add Secret**
5. Now go to **Action > Villain.In.Glasses.RDPv2 (Left Menu) > Run Workflow**

#### Third Step
1. Back to: https://ngrok.com
2. Click On The <a href="https://dashboard.ngrok.com/endpoints">Endpoint</a> Option
3. And Click On The <a href="https://dashboard.ngrok.com/cloud-edge/endpoints">Status</a> Option
4. Copy The URL without "tcp://"
5. The Copied Link Like: 8.tcp.ngrok.io:15003
6. Go To Your RDP Using Software
7. Then Put Your Url
8. Put The Username: runneradmin
9. Put The Password: P@ssw0rd!
10. And Connect it
11. When you are connected dont close the running cmd on the rdp.