# vehicle-network

sample car manufacturer

#Follow these steps to start the network 

1. Once you install hyper ledger composer.

2. Go to fabric-dev-servers and run ./startFabric.sh

3. composer network install --card PeerAdmin@hlfv1 --archiveFile ../Desktop/vehicle-manufacture/vehicle-network/vehicle-network@0.0.1.bna 

4. composer network start --networkName vehicle-network --networkVersion 0.0.1 --networkAdmin admin --networkAdminEnrollSecret adminpw --card PeerAdmin@hlfv1 --file networkadmin.card

5. composer card import --file networkadmin.card

6. composer network ping --card admin@vehicle-network

7. composer-rest-server

8. Explore at http://localhost:3000
