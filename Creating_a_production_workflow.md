# Flow
- Developing -> testing -> deployment -> Developing -> continue

## Development Phase
-	create and change in feature phase
-	create pull requester in Master Branch
-	Used nginx to deploy
## Testing
-	Use Travis CI w master branch
-	Run test
-   checkout .travis.yml for details
-   test on travis ci website (no additional config need other than connecting github repo and travis yml file)

## Deployment
-	Push to AWS elastic Bean for deployment
-   

### Setting up docker volume to map into local dir
-   docker run -  -v $(pwd):/folder_to_map <image_id>
-   ":" responsible for mapping inside container
-   can add another -v to bookmark inside container
