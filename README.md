## Création d'un bot Twitter qui va nous permettre de :
* autoliker/retweeter automatiquement des tweets en fonction de certains critères (hashtags, location, langue,etc.),
* s'auto-abonner à certains comptes particuliers (cela peut être fait en fonction de certains critères comme les hashtags mentionnés, la location de l'utilisateur, la langue,etc.).

#### Bien évidemment, Twitter restreint l'utilisation de bots et risque de très facilement vous exclure pendant un certain temps si vous faites une utilisation trop abusive de ces scripts. Techniquement, les limites de Twitter sont les suivantes :

### The current technical limits for accounts are:

 * Direct Messages (daily): The limit is 1,000 messages sent per day.
 * Tweets: 2,400 per day. The daily update limit is further broken down into smaller limits for semi-hourly intervals. Retweets are counted as Tweets.
 * Changes to account email: 4 per hour.
 * Following (daily): The technical follow limit is 1,000 per day. Please note that this is a technical account limit only, and there are  additional rules prohibiting aggressive following behavior. Read about following limits and prohibited behavior. 
 * Following (account-based): Once an account is following 5,000 other accounts, additional follow attempts are limited by account-specific ratios. 
 
 ### Ces limites sont théoriques mais avec un bot, elles changent. À première vue, il semble que les limites quotidiennes pratiques à ne pas dépasser soient :
 * RT : ~ 400-500
 * Likes : ~ 700-800
 * Follow : ~ 200-500

#### Attention, à ne pas pratiquer le "mass following" sinon, vous ne pourrez plus vous abonner, liker ou retweeter pendant un certain temps (48 ou 71 heures en général).
