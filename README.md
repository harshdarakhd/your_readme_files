# your_readme_files
#Docker Build Container
  -sudo docker build -t image_name .

#Sudo docker run 
  -sudo docker run -d --name encode-decode-ui-local -p 3005:80 encode_decode_ui:0.3 
  -local port is 80
  -your container port is 3005
  -your container name is encode-decode-ui-local
  
#dont require docker run if you are using portainer
  -simply use the portainer click on your container click on duplicate edit and change your container version and deploy
  
 
# your influx2.0 dbr mappping for running query in influx1.0
  -influx2.0 uses the flux database
  -influx1.0 uses QL database
  -so missverion he dont except the commands of v2 in v1
  -i.e why we can map using dbr mapping
  -

############################# INFLUX DB ################################################################

influx v1 dbrp create --db people-counting --rp autogen --bucket-id a681dc0dc3d6dd31 --default --org smarti --token -PfPbsN-HEOL_rH-ydFg_UfSslXjD-ir59yV1WEBITv5SsDovNTK9GmC19CGZ93TQ6MqrDNWoVgx12kc_Qhb9Q==



ID                      Database        Bucket ID               Retention Policy        Default Organization ID
0a133836026a2000        people-counting a681dc0dc3d6dd31        autogen                 true    6f74bb30691fdd56



https://community.influxdata.com/t/how-to-connect-grafana-to-influxdbv2-by-influxql-method/17377/12?u=grant1


##################################### redis setup   ###################################################
 cmd :
  1. docker pull redis:6
  2. docker run -d --name redis -p 6379:6379 redis
  
 - go to the portainer and click on redis container click on duploicate button and choose option first change the port 
 *** Publish all exposed network ports to random host ports ** please unabele this option and disable *** Enable access control  ***
 









############################# INFLUX DB ################################################################

# to use ago, just now time in react js use moment 
  - moment.utc("2019-12-04 12:00:24").local().startOf('seconds').fromNow()
  - moment("20111031", "YYYYMMDD").fromNow(); // 8 years ago
  -moment("20120620", "YYYYMMDD").fromNow(); // 7 years ago
  -moment().startOf('day').fromNow();        // 16 hours ago
  -moment().endOf('day').fromNow();          // in 8 hours
  -moment().startOf('hour').fromNow();  
  
  
  # to convert query time in time format  
    -fetch time convert to string to 
    
    
    ##########################################  react ####################################################
    
    npm i react-router-dom --force   or npm i anylibirary --legacy-peer-deps  // use for unable salved dependency tree error
