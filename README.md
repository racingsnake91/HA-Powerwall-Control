# HA-Powerwall-Control
Place the "tesla_gateway" folder in your custom_compontents folder and restart home assistant.  
  
add the following to your configuration.yaml file and restart home assistant again:  
  
tesla_gateway:  
&nbsp;&nbsp;username: 'your@tesla.email'  
&nbsp;&nbsp;password: 'your-tesla-password'  
&nbsp;&nbsp;access_token: '' #Leave this blank, the component will fill it in and refresh it every time you restart.  
  
