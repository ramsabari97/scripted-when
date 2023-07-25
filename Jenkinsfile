node {
  if(env.BRANCH_NAME == 'main') {
    stage ('Build Master') {
      echo 'Building main'
    }
  }
   if(env.BRANCH_NAME == 'dev') {
    stage ('Build Dev') {
      echo 'Building dev'
    }
  }
}
  
