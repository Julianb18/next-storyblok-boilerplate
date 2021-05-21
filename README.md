## Next.js connected to Storyblok API Boilerplate

Create a new space and retrieve your preview token for that Space. Add the token to your Storyblok client in storyblok.js as the accessToken directly or from an .env file. In this boilerplate I will add my token to '.env' file. 

The content of this file will look something like this:
```javascript
PREVIEW_TOKEN="the-token-from-your-space"
```
### See all your 'Links'

The link below allows you to see all your current Links/Routes in your Storyblok api. Add your token in the place of "your-token-here".
```
https://api.storyblok.com/v1/cdn/links?&starts_with=pages&version=draft&token=your-token-here
```
