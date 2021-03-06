# Serverless

Serverless framework helps developers build serverless applications with less cost and overheads. It provides a powerful and unified experience to develop, deploy and test serverless applications. It basically takes care of the end to end process of application development. 

Serverless applications can be developed and tested on different cloud providers like AWS, Azure and GCP. These applications can then also be secured and monitored. 

CloudPlex has made to it easy deploy serverless applications. Not only deployment, CloudPlex also takes care of the creation process of serverless applications. These serverless applications can also be a part of CloudPlex that can contain services of different types like containers, managed services etc. By making all these different service types a part of single project in CloudPlex, we are making it easier for the user to develop and deploy complex applications using easy to use drag-n-drop interface of platform.

Details of the configurations that can be done for Serverless are explained below and also highlighted in the image.

![1](imgs/1.jpg)

1. **Serverless**: Drop-down to add serverless in canvas. 
2. **Serverless Icon**: Drag and drop the service icon to add in canvas. Click on icon to configure the service.

![2](imgs/2.jpg)

1. **Templates**: To reuse any existing service template.
2. **Name**: Name for the service.
3. **Version**: Version of the service
4. **Namespace**: Namespace for the service.

![3](imgs/3.jpg)

1. **GIT**: Drop-down to select Git profile. You can use any existing or use new profile.
2. **Profile Name**: Profile name for Git.
3. **Repository name** of Git.
4. **Private Key**: Private Key of Git.
5. **Save Git Credentials**: To store the Git profile for future use.

![4](imgs/4.jpg)

1. Specify **Git Url**.
2. Specify **Git Branch**
3. **Registry**: Drop-down to use a New docker registry or any existing one.
4. **Registry Name**: Name of the docker registry.
5. **Registry Username** of the registry.
6. **Registry Password** of the registry.
7. **Save Docker Credentials**: To save docker registry credentials for future use. 

![5](imgs/5.jpg)

1. Specify **Image Url**.
2. Specify **Registry Tag**.
3. **Environment Variables**: To add static/dynamic environment variables or Load Balancer.

![6](imgs/6.jpg)

1. **Minimum Scale:** Minimum scale limit.
2. **Maximum Scale:** Maximum scale limit.
3. **Add Ports**: To add host and ports.
4. To enable **Enforce Internal Communication**.
5. (If **Enforce Internal Communication** is not **Enabled**) **Add Domains**.