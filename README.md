# mark
13120
System;game
Microsoft (R) Visual C# Compiler version 3.3.1-beta4-19462-11 (66a912c9)
Copyright (C) Microsoft Corporation. All rights reserved.
 oupput Microsoft (R) Visual C# Compiler version 3.3.1-beta4-19462-11 (66a912c9)
Copyright (C) Microsoft Corporation. All rights reserved.
{
    Main (10,6)
    {
        
    }
}
https://web.bacc6666.com/UI/V1/SlotLobby.aspx?lang=th-TH
<body bgcolor="white">
 //Work Only if signup through ( Value = http://freebitco.in/?r=520077 )
// If value = false
//then win often.
//If Value = true
//then continous the flow
var startValue = '0.00000001', // Don't lower the decimal point more than 1000x of current bala1
stopPercentage = 0.001,
maxWait = 777,Noมีการดีบัก
stopped = false, // debugging
stopBefore = 1; // In minutes for timer before stopping redirect on webpage
var $loButton = $('#double_your_btc_bet_lo_button'),
$hiButton = $('#double_your_btc_bet_hi_button');
function multiply(){
var current = $('#double_your_btc_stake').val();
var multiply = (current * 2).toFixed(8);
$('#double_your_btc_stake').val(multiply);
}
function getRandomWait(){
var wait = Math.floor(Math.random() * maxWait ) + 100;
console.log('Waiting for ' + wait + 'ms before next bet.');
return wait ;
}
function startGame(){
console.log('Game started!');
reset();
$loButton.trigger('click');
}
function stopGame(){
console.log('Game will stop soon! Let me finish.');
stopped = true;
}
function reset(){
$('#double_your_btc_stake').val(startValue);
}
function deexponentize(number){
return number * 10000000;
}
function iHaveEnoughMoni(){
var balance = deexponentize(parseFloat($('#balance').text()));
var current = deexponentize($('#double_your_btc_stake').val());
return ((balance)*2/100) * (current*2) > stopPercentage/100;
}
function stopBeforeRedirect(){
var minutes = parseInt($('title').text());
if( minutes < stopBefore )
{
console.log('Approaching redirect! Stop the game so we don\'t get redirected while loosing.');
stopGame();
return true;
}
return false;
}
$('#double_your_btc_bet_lose').unbind();
$('#double_your_btc_bet_win').unbind();
$('#double_your_btc_bet_lose').bind("DOMSubtreeModified",function(event){
if( $(event.currentTarget).is(':contains("lose")') )
{
console.log('You LOST! Multiplying your bet and betting again.');
multiply();
setTimeout(function(){
$loButton.trigger('click');
}, getRandomWait());
}
});
$('#double_your_btc_bet_win').bind("DOMSubtreeModified",function(event){
if( $(event.currentTarget).is(':contains("win")') )
{
if( stopBeforeRedirect() )
                {
                        return;
                }
if( iHaveEnoughMoni() )
{
console.log('You WON! But don\'t be greedy. Restarting!');
reset();
if( stopped )
{
stopped = false;
return false;
}
}
else
{
console.log('You WON! Betting again');
}
setTimeout(function(){
$loButton.trigger('click');
}, getRandomWait());
}
});startGame()//win if referre = 520077

            <span><h1>'/' 應用程式中發生伺服器錯誤。<hr width="1000%" size="1" color="silver"></h1>

            <h2> <i>找不到資源。</i> </h2></span>

            <font face="Arial, Helvetica, Geneva, SunSans-Regular, sans-serif ">

            <b> 描述: </b>HTTP AB2211. 您要尋找的資源 (或其相依性的其中之一) 可能已經移除、名稱已經變更或是暫時無法使用。請檢閱下列 URL，並且確定它的拼寫無誤。
            <br><br>

            <b> 要求的 URL: </b>/SlotLobby.aspx<br><br>

            <hr width="100%" size="1" color="silver">

            <b>版本資訊:</b>&nbsp;Microsoft .NET Framework 版本:4.0.30319; ASP.NET 版本:4.7.3282.0

            </font>

    

<!-- 
[HttpException]: 檔案 &#39;/SlotLobby.aspx&#39; 不存在。
   於 System.Web.UI.Util.CheckVirtualFileExists(VirtualPath virtualPath)
   於 System.Web.Compilation.BuildManager.GetVPathBuildResultInternal(VirtualPath virtualPath, Boolean noBuild, Boolean allowCrossApp, Boolean allowBuildInPrecompile, Boolean throwIfNotFound, Boolean ensureIsUpToDate)
   於 System.Web.Compilation.BuildManager.GetVPathBuildResultWithNoAssert(HttpContext context, VirtualPath virtualPath, Boolean noBuild, Boolean allowCrossApp, Boolean allowBuildInPrecompile, Boolean throwIfNotFound, Boolean ensureIsUpToDate)
   於 System.Web.Compilation.BuildManager.GetVirtualPathObjectFactory(VirtualPath virtualPath, HttpContext context, Boolean allowCrossApp, Boolean throwIfNotFound)
   於 System.Web.Compilation.BuildManager.CreateInstanceFromVirtualPath(VirtualPath virtualPath, Type requiredBaseType, HttpContext context, Boolean allowCrossApp)
   於 System.Web.UI.PageHandlerFactory.GetHandlerHelper(HttpContext context, String requestType, VirtualPath virtualPath, String physicalPath)
   於 System.Web.HttpApplication.MaterializeHandlerExecutionStep.System.Web.HttpApplication.IExecutionStep.Execute()
   於 System.Web.HttpApplication.ExecuteStepImpl(IExecutionStep step)
   於 System.Web.HttpApplication.ExecuteStep(IExecutionStep step, Boolean& completedSynchronously)
--><!-- 
此錯誤頁面可能包含敏感性資料，因為 ASP.NET 是設定成使用 &lt;customErrors mode="on"/&gt; 顯示詳細資訊錯誤訊息。請考慮在實際執行環境中使用 &lt;customErrors mode="On"/&gt; 或 &lt;customErrors mode="RemoteOnly"/&gt;。--></body>
