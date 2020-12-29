# CodePen-Switch-entire-tab-by-JavaScript

## 有個需求需要在切Tab時，連整個背景圖片一起置換，故作此JavaScript.
Bootstrap and jQuery are required.

## JavaScript
`//Tabs for "Animal Tabs"
const switchToTabs = function (afterDivId) {
  const animalTabs = document.querySelectorAll("div.container");
  for (let i = 0; i < animalTabs.length; i++) {
    animalTabs[i].style.display = "none";
  }
  $(afterDivId)[0].style.display = "block";
};`

<img src="https://github.com/Sandra-Kao/CodePen-Switch-entire-tab-by-JavaScript/blob/main/ezgif.com-gif-maker.gif">
