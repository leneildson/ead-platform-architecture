# EAD Platform Architecture Resources



# Como utilizar o CloudFormation

- Acesse o recurso CloudFormation na console
- Clique em Create Stack
![imagem](images/criar01.png)
- Selecione "Upload a template file"
![imagem](images/criar02.png)
- Preencha o nome da Stack e os parametros que serão utilizados no template
![imagem](images/criar03.png)
- Em Stack Options, clique em Next.
![imagem](images/criar04.png)
- Agora basta acompanhar os recursos serem criados no console
![imagem](images/criar05.png)
# VPC

Para criar a VPC, baixe o template dentro da pasta template/vpc.template 

**Lembre-se de definir as redes sem que ocorra overlap entre as redes do datacenter atual.**
# EKS

Para criar o Cluster de EKS, recomendo seguir o step-by-step da página a seguir: 

https://github.com/BRPSNPO/seminars-aws-series-1/tree/master/05-containers-na-aws#eks
# EC2

Para criar a VPC, baixe o template dentro da pasta template/ec2.template

**Se atente a AMI, ela corresponde a imagem do sistema operacional**


# ElasticCache

To be done
