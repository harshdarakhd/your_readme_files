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

############################# INFLUX DB ################################################################

# to use ago, just now time in react js use moment 
  - moment.utc("2019-12-04 12:00:24").local().startOf('seconds').fromNow()
