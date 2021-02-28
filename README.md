# HA-Powerwall-Control
Place the "tesla_gateway" folder in your custom_compontents folder and restart home assistant. 

add the following to your configuration.yaml file and restart home assistant again:

tesla_gateway:
  username: 'your@tesla.email'
  password: 'your-tesla-password'
  access_token: '' #Leave this blank, the component will fill it in and refresh it every time you restart. 
  
