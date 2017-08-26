Branchster-Android
==================

## Configuring Keys and Secrets
To set up your own API keys and get rid of this error:

1. Open up **api_keys.xml** which exists in the */res/values* folder.
2. Insert your Branch App Key
3. Clean/Rebuild your project.

```XML
<resources>

    <!--
    Your Branch App Key Goes Here
    If you don't have one, see the Branch Android Quick-Start for how to get one:
    https://github.com/BranchMetrics/Branch-Integration-Guides/blob/master/android-quick-start.md
    -->

    <!-- Old Branch Monster Factory App keys.-->
    <!--<string name="branch_key">key_live_gchnKkd3l3m9YBPP2d73jmfejkcgVjgM</string>-->
    <!--<string name="branch_key_test">key_test_lkhEVOq9sPU9FXgbSAoQthfhqsd5EVaV</string>-->

    <!-- Branchster app keys-->
    <string name="branch_key">YOUR BRANCH LIVE KEY</string>
    <string name="branch_key_test">YOUR BRANCH TEST KEY</string>

    <!--
    Your Twitter Key and Secret Goes Here
    If you don't have these, see the Twitter Kit for Android documentation:
    https://dev.twitter.com/twitter-kit/android
    -->
    <string name="twitter_key">YOUR TWITTER APP KEY</string>
    <string name="twitter_secret">YOUR TWITTER APP SECRET</string>

</resources>
```

### Facebook App ID

1. Open up **strings.xml** which exists in the */res/values* folder.
2. Insert your Facebook App ID
3. Clean/Rebuild your project.

```XML
<string name="facebook_app_id">YOUR FB APP ID</string>
```
