---
layout: page
title: Donate
permalink: /donate/
menu: true
---

Cosma dreams about soft comfortable cats bed. You can help us to buy her one. :)

<form method="POST" action="https://money.yandex.ru/quickpay/confirm.xml" class="pure-form pure-form-stacked" target="_blank">
    <fieldset>
        <input type="hidden" name="receiver" value="410011261306506"> 
        <input type="hidden" name="formcomment" value="Project: Cosma Cat"> 
        <input type="hidden" name="short-dest" value="Project: Cosma Cat"> 
        <input type="hidden" name="quickpay-form" value="donate"> 
        <input type="hidden" name="targets" value="New staff for Cosma"> 
        <input type="hidden" name="successURL" value="http://cosmacat.ru/thankyou/">
        
        <div class="pure-g">
            <label class="pure-u-1 pure-u-md-1-4 field-label">Sum</label>
            <input class="pure-u-1 pure-u-md-1-2" type="text" name="sum" value="" data-type="number" maxlength="6" placeholder="Sum (rub.)">
            <div class="pure-u-md-1-4"></div>

            <label class="pure-u-1 pure-u-md-1-4 field-label">Comment</label>
            <input class="pure-u-1 pure-u-md-1-2" type="text" name="comment" value="" placeholder="Your comment">
            <div class="pure-u-md-1-4"></div>       
        
            <div class="pure-u-md-1-4"></div>
            <div class="pure-u-1 pure-u-md-1-2 payment-methods">
                <div class="pure-u-1-3">
                    <input id="radio01" type="radio" checked name="paymentType" value="AC" title="VISA, MasterCard">        
                    <label for="radio01" class="payment payment-bank"></label>
                </div><div class="pure-u-1-3">
                    <input id="radio02" type="radio" name="paymentType" value="MC" title="Megafon, MTS, Beeline"> 
                    <label for="radio02" class="payment payment-mobile"></label>
                </div><div class="pure-u-1-3">   
                    <input id="radio03" type="radio" name="paymentType" value="PC" title="Yandex.Money">  
                    <label for="radio03" class="payment payment-yamoney"></label> 
                </div>
            </div> 
            <div class="pure-u-md-1-4"></div>          

            <div class="pure-u-md-1-4"></div>
            <input class="pure-button button-green pure-u-1 pure-u-md-1-2" type="submit" value="Donate">
            <div class="pure-u-md-1-4"></div>
            
        </div>
    </fieldset>
</form>