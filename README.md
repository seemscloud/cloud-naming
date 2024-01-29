# Cloud Naming

## Environments

| Long Name  	| Short Name 	| Use in Name 	| Use in Tags / Description 	|
|------------	|------------	|-------------	|---------------------------	|
| Production 	| prod       	|      X      	|                           	|
|            	| production 	|             	|             X             	|
| UAT        	| uat        	| X           	| X                         	|
| Staging    	| stg        	| X           	|                           	|
|            	| staging    	|             	| X                         	|
| Test       	| test       	| X           	| X                         	|
| Dev        	| dev        	| X           	| X                         	|
|            	|            	|             	|                           	|

## VM Grouping

| Group       	| Cloud 	| Resource                  	| Template                           	| Examples                   	|
|-------------	|-------	|---------------------------	|------------------------------------	|----------------------------	|
| VM Grouping 	| GCP   	| Instance Group            	| ig-STACK-PART(-ENVIRONMENT)        	| ig-myproj-jboss            	|
|  	            |      	  |                             |                                     | ig-myproj-jboss-prod       	|
|             	| Azure 	| Virtual Machine Scale Set 	| vmss-STACK-PART-REGION-ENVIRONMENT 	| vmss-myproj-jboss-weu-prod 	|
|             	| AWS   	| Auto Scaling Group        	| TBD                                	| TBD                        	|
