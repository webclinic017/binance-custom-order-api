## How it works    
  
This application sends buy and sell orders to Binance according to posted order information formatted into JSON.  
I'm not sure but something like this. 
  
{   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"type":"Entry",  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"side":"BUY",   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"leverage":3,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"symbol":"BTCUSDT"  
}  

## Deploy
1, Push to Github.  
2, Go to Heroku and set "Reveal Config Vars".
3, Select your repository to deploy. 
  
That's... it...  way too easy.  

## Environment variable  
Please check "env.todo" file in the root directory.   

## Disclaimer
The ordering logic is customized complicatedly.  
Consider this app as a mock.
I don't care whatever happens to you because of this system.