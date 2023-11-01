node
{
   def buildNumber = BUILD_NUMBER
stage("Git CheckOut"){
        git url: 'https://github.com/appamma16/myproject.git',branch: 'main'
    }

stage(" Maven Clean Package"){
      def mavenHome=  tool name: "Maven", type: "maven"
      def mavenCMD = "${mavenHome}/bin/mvn"
sh "${mavenCMD} clean package"
    } 
