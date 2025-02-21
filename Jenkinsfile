pipeline {
 agent any
 stages{
   stage ('Prepare'){
     steps{
       echo "准备环境"
     }
   } 
   stage ('Checkout'){
     steps{
       echo "获取代码"
     }
   }
   stage ('Build'){
     steps{
       echo "构建镜像"
     }
   }
   stage ('Deploy'){
     steps{ 
       echo "部署项目"
     }
     }
   stage ('Test'){
     steps{
       echo "测试效果"
     }
   }
 }
}
