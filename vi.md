<link rel="stylesheet" href="style.css">

# vi - coverage report

<table>
<thead>
    <tr>
        <th>File</th>
        <th colspan="2">Translation coverage</th>
    </tr>
</thead>
<tbody>
    <tr><td><a href="#">frontend</a></td><td>83.65%</td><td>
        <div class="pb">
            <span class="pb-fill" style="width: 83.65%;"></span>
        </div>
    </td></tr>
    <tr><td><a href="#">game</a></td><td>90.67%</td><td>
        <div class="pb">
            <span class="pb-fill" style="width: 90.67%;"></span>
        </div>
    </td></tr>
    <tr><td><a href="#">supporter</a></td><td>0%</td><td>
        <div class="pb">
            <span class="pb-fill" style="width: 0%;"></span>
        </div>
    </td></tr>
    <tr><td><a href="#">web</a></td><td>84.8%</td><td>
        <div class="pb">
            <span class="pb-fill" style="width: 84.8%;"></span>
        </div>
    </td></tr>
</tbody></table>

-----------------------

## Frontend

**Missing in vi/frontend.php:**

```
'loginFail2' => 'Not logged in! You\'re playing as a guest called {name}.',
'noBlocks' => 'Out of blocks',
'noBlocks2' => 'All blocks were used',
'fr' => 'Friends',
'frLoad' => 'Loading friend list',
'frLogin' => 'Log in first to use friend list',
'frEmpty' => 'Friend list is empty',
'frHowAdd' => 'Visit user\'s profile to send friend request.',
'frPriv' => 'Private',
'frIn' => 'Already in!',
'frChat' => 'Open chat',
'frRel' => 'Reload',
'frMsgTo' => 'Message to {name}',
'frInv' => 'Send room invite',
'frInvTo' => 'Invite to join {room}',
'frInvIn' => 'You are already in!',
'frInvBy' => 'by {user}',
'frOn' => 'ONLINE',
'frOff' => 'OFFLINE',
'frNewChatH' => 'This is the beginning of chat history with {name}.',
'frWelc' => 'Welcome to the Friends tab',
'frIntro' => 'In this area you can access a list of online friends, private chats, and room invites',
'frIntro2' => 'To send a friend request, visit a user\'s profile',
'frIntro3' => 'To manage friends, visit the {frPage}',
'frPage' => 'Friends page',
'frIntroCl' => 'Close intro',
```

## Game

**Missing in vi/game.php:**

```
'skin' => 'Skin',
'skin2' => 'Block skin',
'sound' => 'Sound',
'enableVSE' => 'Voice comments',
'rotateSE' => 'Sound effect of block rotation',
'DMsound' => 'Direct message notification',
'guestRooms' => 'Guest rooms',
'bots' => 'Bots',
'rulesets' => 'Rulesets',
'solidGarbageSpeed' => 'Solid g. speed',
'gapWidth' => 'Gap width',
'gInv' => 'Invert garbage',
'lines' => 'Lines',
'statistics' => 'Stats',
'vs' => 'VS',
'downstack' => 'garbage downstack',
'wasted' => 'Wasted',
'expand' => 'Expand',
```

## Supporter

**Missing in vi/supporter.php:**

```
'donate' => 'Donate',
'supportUs' => 'Support Us',
'descr' => 'Support Jstris and enable the Supporter rewards',
'supportJstris' => 'Support Jstris',
'supportDesc1' => 'If you appreciate this game, please consider becoming Supporter of this project and help cover server expenses and further development.',
'warnDelay' => 'It may take up to 10 minutes until the transaction is credited to your Jstris account. Then you can configure your Supporter benefits here.',
't1Full' => 'Tier 1 Supporter',
't2Full' => 'Tier 2 Supporter',
't1' => 'Tier 1',
't2' => 'Tier 2',
'nameIcon' => 'Name icon',
'nameIconDesc' => 'Select one of 10 icons (incl. your country flag) that will show before your name.',
'emotes' => 'Emotes in chat',
'emotesDesc' => 'By typing <code>:</code> in jstris chat, emote selection will open with 2000+ available emotes from the Openmoji Library.',
'discord' => 'Role on Jstris discord',
'discordDesc' => 'Orange name on Jstris Discord server. Only applicable if you link Discord account to Jstris.',
'list' => 'Name on the Supporters list',
'listDesc' => 'A link to your in-game profile will be included in the list of supporters. Can be disabled in the settings.',
'customColor' => 'Custom color in chat',
'customColorDesc' => 'You can set any name color you want using a color picker tool.',
'moreIcons' => '2000+ name icons',
'moreIconsDesc' => 'You can set any of the 2000+ emoji icons from the Openmoji Library as the icon before your name in the game and on the website. You can also enable random icon selection each time you load the game.',
'blockSkins' => '100+ more block skins',
'blockSkinsDesc' => '100+ More block skins will be available in the in-game Appearance settings. This skin selection will be visible to other players and in your replays.',
'changeName' => 'Option to change username',
'changeNameDesc' => 'Option to change user name once a month.',
'allFromT1' => 'and everything from Tier 1',
'perMonth' => ':cost per month',
'customAmount' => 'Custom amount',
'customAmountDesc' => 'You may become Supporter with a one-time transaction or a custom amount. In case of one-time, the Supporter benefits are assigned to your account for a duration based on the amount.',
'oneTime' => 'One time',
'monthly' => 'Monthly',
'other' => 'Other',
'estimate' => 'Show estimate',
'dAmount' => 'Donation amount',
'sDuration' => 'Supporter duration',
'learnMore' => 'Learn more',
'paymentsInfo' => 'Processed via :service_name.&nbsp; Can be cancelled anytime on account dashboard.',
'gift' => 'Gift rewards',
'giftDesc' => '',
'giftTo' => 'Gift to account',
'set' => 'Set',
'rewardsAvailable' => 'Supporter rewards available',
'rewardsList' => 'Thanks for your donation to Jstris! You may enable the following rewards.',
'monthlyActive' => 'You currently have :type subscription active.',
'customActive' => 'You have :type rewards enabled for :days days based on the donation amount.',
'ingameIcon' => 'In-game icon',
'countryFlag' => 'Country flag',
'iconEmote' => 'Custom emote as in-game icon',
'iconEmoteDesc' => 'Start typing to search. Visit :link for full list of emote names.',
'randIcon' => 'Select a new icon randomly every time the game is loaded',
'chatColor' => 'Custom in-game name color',
'supporterList' => 'Username mentioned in the Supporters list',
'roleAdded' => 'Added to your connected Discord account :name.',
'addDiscord' => 'Add your Discord account in the <a href=":link">Jstris account settings</a> before enabling.',
'apply' => 'Apply changes',
```

## Web

**Missing in vi/web.php:**

```
'friends' => 'Friends',
'mostGames' => 'The most games',
'userRanking' => 'Ranking stats',
'wasteDesc' => 'Ratio of T pieces not used in a T-Spin (to total T pieces)',
'reportU' => 'Report user',
'reportDesc' => ' Here you can create a report if you think someone has abused the game chat.',
'user' => 'User',
'reason' => 'Reason',
'rr0' => 'Spam or unwanted advertising',
'rr1' => 'Sexually explicit content',
'rr2' => 'Hate speech',
'rr3' => 'Harassment or bullying',
'rr4' => 'Other (specify)',
'sendReport' => 'Send report',
'accept' => 'Accept',
'ignore' => 'Ignore',
'pending' => 'Pending Requests',
'frFilter' => 'Filter Names',
'noPending' => 'At the moment you have no pending friend requests.',
'onlineNow' => 'Online now',
'recentlyAc' => 'Recently active',
'lastActive' => 'Active :when',
'noFriends' => 'At the moment your friend list is empty.',
'ruSure' => 'Are you sure?',
'rmFriend' => 'Do you want to remove this person from your friend list?',
'rmConfirm' => 'Yes, remove',
```

