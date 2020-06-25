
## Push To Talk PWA Plugin

#### Reach out with accuracy

Website contact forms have always been crap. This was solved for the 
most part by apps like Facebook Messenger, offering simpler, more personal, 
and more fun ways of connecting customers with business owners

Why solve it again? There are some very real problems to running your 
Customer Service on Social Media, even though it's easy. 
First of all control. You're giving it away. 
Not to mention the 95% of the data you don't care about. 
And to whom? What do you owe them?

##### Requirements

This is currently a React Component designed to be used as a plugin in an 
Open Source Progressive Web App project called [Whitelabel PWA](https://github.com/listingslab-software/whitelabel-pwa)

##### Install and use

> * apiKey is not currently required, but that will change

1. Install the [GitHub package](https://github.com/listingslab-software/pushtotalk/packages/281880) 
into your project

```bash
cd <your-project>
npm install @listingslab-software/pushtotalk@0.0.9
```

2. Add an instance of **<PushToTalk />** to the highest level you can in your app, 
ideally the entry point

```javascript

<PushToTalk options={{
	api: `https://api.listingslab.com`,
	apiKey:`643464ff-531d-4686-af83-4480b1953bd5`,
}}/>

```
