/*BEGIN Xbox One Controller Styling*/
.controller.xbox {
    background: url(https://imgur.com/foGwmky.png);
    height: 630px;
    width: 750px;
    /*    margin-left: -375px;
        margin-top: -285px;*/
}

.xbox.white {
    background: url(xbox-assets/base-white.svgz);
}

.xbox.disconnected {
    background: url(xbox-assets/disconnected.svgz);
}

.xbox.disconnected div {
    display: none;
}

.xbox .triggers {
    width: 446px;
    height: 121px;
    position: absolute;
    left: 152px;
}

.xbox .trigger {
    width: 88px;
    height: 121px;
    background: url(https://imgur.com/8y3sYfr.png);
    opacity: 0;
}

.xbox .trigger.left {
    float: left;
    background-position: 0 0;
}

.xbox .trigger.right {
    float: right;
    transform: rotateY(180deg);
}

.xbox .bumper {
    width: 170px;
    height: 61px;
    background: url(https://imgur.com/XHWE13h.png);
    opacity: 0;
}

.xbox .bumpers {
    position: absolute;
    width: 536px;
    height: 61px;
    left: 107px;
    top: 129px;
}

.xbox .bumper.pressed {
    opacity: 1;
}

.xbox .bumper.left {
    float: left;
}

.xbox .bumper.right {
    float: right;
    -webkit-transform: rotateY(180deg);
    transform: rotateY(180deg);
}

.xbox .quadrant {
    position: absolute;
    background: url(https://imgur.com/hHM6boD.png);
    height: 45px;
    width: 45px;
    top: 258px;
    left: 354px;
    z-index: 0;
}

.xbox .p0 {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
}

.xbox .p1 {
    -webkit-transform: rotate(90deg);
    transform: rotate(90deg);
}

.xbox .p2 {
    -webkit-transform: rotate(270deg);
    transform: rotate(270deg);
}

.xbox .p3 {
    -webkit-transform: rotate(180deg);
    transform: rotate(180deg);
}

.xbox .arrows {
    position: absolute;
    width: 141px;
    height: 33px;
    top: 264px;
    left: 306px;
}

.xbox .back, .xbox .start {
    background: url(https://imgur.com/biO0E24.png);
    width: 33px;
    height: 33px;
    opacity: 0;
}

.xbox .back.pressed, .xbox .start.pressed {
    opacity: 1;
}

.xbox .back {
    float: left;
}

.xbox .start {
    background-position: 33px 0px;
    float: right;
}

.xbox .abxy {
    position: absolute;
    width: 153px;
    height: 156px;
    top: 192px;
    left: 488px;
}

.xbox .button {
    position: absolute;
    background: url(https://imgur.com/mqyZaR9.png);
    width: 48px;
    height: 48px;
}

.xbox .button.pressed {
    background-position-y: -48px;
    margin-top: 5px;
    opacity: 1;
}

.xbox .a {
    background-position: 0 0;
    top: 108px;
    left: 55px;
}

.xbox .b {
    background-position: -49px 0;
    top: 58px;
    right: 0px;
}

.xbox .x {
    background-position: -98px 0;
    top: 58px;
    left: 4px;
}

.xbox .y {
    background-position: 48px 0;
    left: 55px;
    top: 7px;
}

.xbox .sticks {
    position: absolute;
    width: 371px;
    height: 196px;
    top: 239px;
    left: 144px;
}

.xbox .stick {
    position: absolute;
    background: url(https://imgur.com/V2BqYPK.png);
    background-position: -85px 0;
    height: 83px;
    width: 83px;
}

.xbox .stick.pressed {
    background-position: 0 0;
}

.xbox .stick.left {
    top: 0;
    left: 0;
}

.xbox .stick.right {
    top: 113px;
    left: 288px;
}

.xbox .dpad {
    position: absolute;
    width: 110px;
    height: 111px;
    top: 345px;
    left: 223px;
}

.xbox .face {
    background: url(https://imgur.com/NTq2GSn.png);
    position: absolute;
    opacity: 0;
}

.xbox .face.pressed {
    opacity: 1;
}

.xbox .face.up {
    background-position: 34px 0;
    left: 38px;
    top: 0px;
    width: 34px;
    height: 56px;
}

.xbox .face.down {
    left: 38px;
    bottom: 0;
    width: 34px;
    height: 56px;
}

.xbox .face.left {
    background-position: 0 -93px;
    width: 55px;
    height: 35px;
    top: 38px;
    left: 0;
}

.xbox .face.right {
    background-position: 0 -57px;
    width: 55px;
    height: 35px;
    top: 38px;
    right: 0;
}

.xbox.half {
    margin-top: -315px;
}

.xbox {
    background: no-repeat center;
}

/*END Xbox One Controller Styling*/]

