<h1> AWS-Quick-Setup-Templates </h1>
<hr>
<h2> 목적 </h2>

<p> 전체적인 시스템이 복잡해짐에 따라, 적절한 AMI를 설정하고, 역할을 배분하고, 모든 리소스를 옳바르게 배치하는 것이 점점 더 어려워지게 되었습니다. 그래서 AWS를 어떻게 구성해야할지 잘 모르는 사람도 쉽게 사용할 수 있게 AWS 내에서 보편적으로 사용되는 기본적인 서비스 아키텍처를 CloudFormation 템플릿을 이용해 보다 쉽게 구성할 수 있게 만들고자 시작하였습니다.</p>

<p> CloudFormation을 사용하게 되면 템플릿을 이용해 단 한번에 모든 리소스를 생성할 수 있으며, 변경 이력을 관리할 수 있게 됩니다. 또한 cost estimation을 통해 전체 리소스를 구성했을 때 예상되는 비용도 한 꺼번에 예측할 수 있습니다. 다양한 리전에 비슷한 리소스 구성을 할 때도 간편하게 설정할 수 있다는 장점을 가지며 필요에 따라 커스터마이징도 가능합니다.</p> 
<br>


<br>
<img src="https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram_CloudFormation.ad3a4c93b4fdd3366da3da0de4fb084d89a5d761.png" alt="CloudFormation Process">

<br>
<h2> 참고 링크 </h2>
<p> AWS CloudFormation에서 템플릿 업로드 하는 방법: <a href="http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-using-console-create-stack-template.html">어떻게 CloudFormation 템플릿을 업로드 하는가?</a>
