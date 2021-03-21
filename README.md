# ChromaSlate
A *chroma* version of [Slate](https://github.com/DiscordStyles/Slate/) created by [Gibbu](https://github.com/Gibbu) and [Tropical](https://github.com/Tropix126). I made this because I was bored and I thought it would be a good idea to make this lol, I'm also planning to make a chroma version of [Nocturnal](https://github.com/codedotspectra/themes) :flushed:

# Fun Fact
- I spent hours coding this and it's still not finished yet, I'm still adding things into this addon or is this considered a theme?

# Code
```css
/* Chroma Animations */
@keyframes chroma {
    0% {color: red;}
    10% {color: orangered;}
    20% {color: orange;}
    30% {color: yellow;}
    40% {color: yellowgreen;}
    50% {color: turquoise;}
    75% {color: blue;}
    90% {color: rgb(147, 4, 248);}
    100% {color: rgb(255, 0, 55);}
}
@keyframes chroma-bg {
    0% {background: red;}
    10% {background: orangered;}
    20% {background: orange;}
    30% {background: yellow;}
    40% {background: yellowgreen;}
    50% {background: turquoise;}
    75% {background: blue;}
    90% {background: rgb(147, 4, 248);}
    100% {background: rgb(255, 0, 55);}
}
@keyframes chroma-shadow {
    0% {box-shadow: inset 0 -3px 0px red;}
    10% {box-shadow: inset 0 -3px 0px orangered;}
    20% {box-shadow: inset 0 -3px 0px orange;}
    30% {box-shadow: inset 0 -3px 0px yellow;}
    40% {box-shadow: inset 0 -3px 0px yellowgreen;}
    50% {box-shadow: inset 0 -3px 0px turquoise;}
    75% {box-shadow: inset 0 -3px 0px blue;}
    90% {box-shadow: inset 0 -3px 0px rgb(147, 4, 248);}
    100% {box-shadow: inset 0 -3px 0px rgb(255, 0, 55);}
}
@keyframes chroma-border-top {
    0% {border-top: thin solid rgb(255, 0, 0);}
    10% {border-top: thin solid rgb(255, 68, 0);}
    20% {border-top: thin solid rgb(255, 166, 0);}
    30% {border-top: thin solid rgb(255, 255, 0);}
    40% {border-top: thin solid rgb(170, 255, 0);}
    50% {border-top: thin solid rgb(0, 255, 229);}
    75% {border-top: thin solid rgb(0, 0, 255);}
    90% {border-top: thin solid rgb(149, 0, 255);}
    100% {border-top: thin solid rgb(255, 0, 55);} 
}
@keyframes chroma-border-color {
    0% {border-color: rgb(255, 0, 0);}
    10% {border-color: rgb(255, 68, 0);}
    20% {border-color: rgb(255, 166, 0);}
    30% {border-color: rgb(255, 255, 0);}
    40% {border-color: rgb(170, 255, 0);}
    50% {border-color: rgb(0, 255, 229);}
    75% {border-color:  rgb(0, 0, 255);}
    90% {border-color:  rgb(149, 0, 255);}
    100% {border-color: rgb(255, 0, 55);} 
}
@keyframes chroma-fill {
    0% {fill: red;}
    10% {fill: orangered;}
    20% {fill: orange;}
    30% {fill: yellow;}
    40% {fill: yellowgreen;}
    50% {fill: turquoise;}
    75% {fill: blue;}
    90% {fill: rgb(147, 4, 248);}
    100% {fill: rgb(255, 0, 55);}
}
@keyframes chroma-bg-color {
    0% {background-color: red;}
    10% {background-color: orangered;}
    20% {background-color: orange;}
    30% {background-color: yellow;}
    40% {background-color: yellowgreen;}
    50% {background-color: turquoise;}
    75% {background-color: blue;}
    90% {background-color: rgb(147, 4, 248);}
    100% {background-color: rgb(255, 0, 55);}
}
@keyframes chroma-transparent {
    0% {background-color: rgba(255, 0, 0, 0.1);}
    10% {background-color: rgba(255, 68, 0, 0.1);}
    20% {background-color: rgba(255, 166, 0, 0.1);}
    30% {background-color: rgba(255, 255, 0, 0.1);}
    40% {background-color: rgba(170, 255, 0, 0.1);}
    50% {background-color: rgba(0, 255, 229, 0.1);}
    75% {background-color: rgba(0, 0, 255, 0.1);}
    90% {background-color: rgba(149, 0, 255, 0.1);}
    100% {background-color:rgba(255, 0, 55, 0.1);} 
}

/* Server List */
#app-mount .guilds-1SWlCJ [class*=pill] span {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .guilds-1SWlCJ .homeIcon-tEMBK1 {
    animation: chroma-bg 7s ease-in-out infinite;
}
#app-mount .guilds-1SWlCJ .guildSeparator-3s64Iy {
    animation: chroma-bg 7s ease-in-out infinite;
}
.childWrapper-anI2G9 {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .guilds-1SWlCJ .circleIconButton-jET_ig {
    animation: chroma 7s ease-in-out infinite;
}

/* Channels and shit */
#app-mount .sidebar-2K8pFh .unread-2lAfLh {
    animation: chroma-bg 7s ease-in-out infinite;
}
#app-mount .sidebar-2K8pFh .wrapper-2jXpOf.modeSelected-346R90 .content-1x5b-n {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .sidebar-2K8pFh .containerDefault-3tr_sE .wrapper-PY0fhH svg, #app-mount .sidebar-2K8pFh .containerDefault-3tr_sE .wrapper-PY0fhH .name-3l27Hl, #app-mount .sidebar-2K8pFh .containerDefault-3tr_sE .wrapper-PY0fhH .container-2ax-kl, #app-mount .sidebar-2K8pFh .containerDragAfter-3TEhpe .wrapper-PY0fhH svg, #app-mount .sidebar-2K8pFh .containerDragAfter-3TEhpe .wrapper-PY0fhH .name-3l27Hl, #app-mount .sidebar-2K8pFh .containerDragAfter-3TEhpe .wrapper-PY0fhH .container-2ax-kl, #app-mount .sidebar-2K8pFh .containerDragBefore-3Dzc5x .wrapper-PY0fhH svg, #app-mount .sidebar-2K8pFh .containerDragBefore-3Dzc5x .wrapper-PY0fhH .name-3l27Hl, #app-mount .sidebar-2K8pFh .containerDragBefore-3Dzc5x .wrapper-PY0fhH .container-2ax-kl, #app-mount .sidebar-2K8pFh .containerUserOver-1Tcb7l .wrapper-PY0fhH svg, #app-mount .sidebar-2K8pFh .containerUserOver-1Tcb7l .wrapper-PY0fhH .name-3l27Hl, #app-mount .sidebar-2K8pFh .containerUserOver-1Tcb7l .wrapper-PY0fhH .container-2ax-kl {
    animation: chroma 7s ease-in-out infinite;
}
.root-SR8cQa .activity-1ythUs .customStatusText-39gdCI .customStatus-154i-H span {
    animation: chroma 7s ease-in-out infinite;
}

.root-SR8cQa .header-QKLPzZ .headerInfo-30uryT + div[role=button]:after, .root-SR8cQa .header-QKLPzZ .headerInfo-30uryT + button + div[role=button]:after {
    animation: chroma 7s ease-in-out infinite;
}

/* Chat - Mentions & ETC */
#app-mount .wrapper-2a6GCs.mentioned-xhSam7 {
    animation: chroma-transparent 7s ease-in-out infinite;
}
#app-mount .wrapper-2a6GCs.mentioned-xhSam7:before {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .reactions-12N0jA .reaction-1hd86g.reactionMe-wv5HKu {
    animation: chroma-transparent 7s ease-in-out infinite;
    animation: chroma-border-color 7s ease-in-out infinite;
}
#app-mount .wrapper-2a6GCs .timestamp-3ZCmNB, #app-mount .wrapper-2a6GCs .timestamp-1E3uAL {
    animation: chroma 7s ease-in-out infinite;
}

/* User Popout */
#app-mount .input-2A_zIr, #app-mount .input-cIJ7To, #app-mount .input-1ppKdn {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .userPopout-3XzG_A .headerNameWrapper-3res2c .headerName-fajvi9 {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .userPopout-3XzG_A .headerTag-2pZJzA span:not(.botText-1526X_):not(.username-2b1r56) {
    animation: chroma 7s ease-in-out infinite;
}
.selected-aXhQR6 .layout-2DM8Md {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .userPopout-3XzG_A .bodyTitle-Y0qMQz, #app-mount .userPopout-3XzG_A .headerText-1HLrL7 {
    animation: chroma 7s ease-in-out infinite;
}
.root-SR8cQa .body-3ND3kc .infoScroller-3EYYns .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 a:after {
    animation: chroma 7s ease-in-out infinite;
}

.root-SR8cQa .body-3ND3kc .infoScroller-3EYYns .userInfoSection-2acyCx .connectedAccounts-repVzS .connectedAccount-36nQx7 img[alt="Youtube Logo" i] {
    background: red;
}

.root-SR8cQa .body-3ND3kc .listScroller-2_vlfo .listRow-hutiT_ .listRowContent-3Kih4Q .guildNick-3uAm3i {
    animation: chroma 7s ease-in-out infinite;
}

.wrapper-3t9DeA rect[fill="#f04747"], .wrapper-3t9DeA rect[fill="rgba(240, 71, 71, 1)"], .wrapper-3t9DeA rect[mask*=dnd] {
    animation: chroma-fill 7s ease-in-out infinite;
}

.root-SR8cQa .header-QKLPzZ .headerInfo-30uryT .profileBadges-2vWUYb::before {
    animation: chroma-border-top 7s ease-in-out infinite !important;
}

.root-SR8cQa .header-QKLPzZ .headerInfo-30uryT .nameTag-2IFDfL .discriminator-xUhQkU {
    animation: chroma 7s ease-in-out infinite;
}

.root-SR8cQa .header-QKLPzZ + div[class] .tabBarContainer-1s1u-z .tabBar-2MuP6- .item-PXvHYJ.selected-3s45Ha, .root-SR8cQa .header-QKLPzZ + div[class] .tabBarContainer-1s1u-z .tabBar-2MuP6- .item-PXvHYJ[style*="rgb(255, 255, 255)"] {
    animation: chroma-shadow 7s ease-in-out infinite;
}

/* Settings */
#app-mount .layer-3QrUeG[aria-label*=SETTINGS] .sidebarRegion-VFTUkN .item-PXvHYJ.selected-3s45Ha, #app-mount .layer-3QrUeG[aria-label*=RTC] .sidebarRegion-VFTUkN .item-PXvHYJ.selected-3s45Ha {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount [role=radiogroup] .item-26Dhrx[aria-checked=true] {
    border-color: var(--base-border);
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .slider-1PF9SW .grabber-3mFHz2 {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .slider-1PF9SW .barFill-23-gu- {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
#app-mount .colorHeaderSecondary-3Sp3Ft {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .layer-3QrUeG[aria-label=USER_SETTINGS] .connection-1fbD7X .connectionAccountValue-3VdBGs {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .layer-3QrUeG[aria-label*=SETTINGS] .contentRegion-3nDuYy::before, #app-mount .layer-3QrUeG[aria-label*=RTC] .contentRegion-3nDuYy::before {
    animation: chroma 7s ease-in-out infinite;
}
#app-mount .layer-3QrUeG[aria-label=USER_SETTINGS] .side-8zPYf6 > .item-PXvHYJ:before {
    color: white !important;
}

/* Addon Errors */
.bd-modal-wrapper .bd-modal .tab-bar-container .tab-bar-item.selected {
    animation: chroma-shadow 7s ease-in-out infinite;
}
#app-mount .lookFilled-1Gx00P, #app-mount .bd-modal-wrapper .footer button, #app-mount .primaryButton-2BsGPp {
    animation: chroma-bg-color 7s ease-in-out infinite;
}
.bd-modal-wrapper .bd-modal .bd-modal-inner .header .title {
    animation: chroma 7s ease-in-out infinite;
}
.bd-modal-wrapper .bd-modal .bd-modal-inner .bd-modal-body .scroller .errors .error .table-column.column-error .error-link {
    animation: chroma 7s ease-in-out infinite;
}
.bd-modal-wrapper .bd-modal .bd-modal-inner .bd-modal-body .scroller .errors:empty:after {
    content: "No errors here.";
    animation: chroma 7s ease-in-out infinite;
}
```
