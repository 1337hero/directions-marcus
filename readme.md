### Login to Cloudflare:

`https://dash.cloudflare.com/login`

### Click on your domain from the account home:

![img1](/img/img1.png)

### Then Click DNS from the left hand side bar.

![img2](/img/img2.png)

You will need to edit two A records that should have an old IP in them `138.68.233.224`

One A record will be @ for root with new IP `143.198.155.134`

Second A record will be www with new IP `143.198.155.134`

Proxy should be enabled (orange)

Hit SAVE

![img3](/img/img3.png)

That should be all, might take up to 45 mins before DNS resolves.... 
