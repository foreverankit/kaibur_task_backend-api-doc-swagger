# Kaiburr_task_backend-api-doc-swagger

Here we will document our api using swagger. Swagger is just an amazing tool to document our api. This is really helpful for the client side developer as he can easily see what methods to call in the client side. We will be generating html format documentation with the help of swagger.

## We will just add the following dependency to pom.xml and pom.xml will look like this.

![Screenshot from 2020-02-20 03-09-22](https://user-images.githubusercontent.com/31029148/74879086-70bb3580-538e-11ea-8df3-81afc5a92eb1.png)

## In the main class add the following annotation @EnableSwagger2

![Screenshot from 2020-02-20 03-10-47](https://user-images.githubusercontent.com/31029148/74879185-9f391080-538e-11ea-8c3d-aa1591a12cd4.png)


We are all set to go. Dont forget to run clean maven build. Now rerun the server again and we will see the following output in the link - http://localhost:8080/swagger-ui.html#/. After opening the link will look like this.

![Screenshot from 2020-02-20 03-14-28](https://user-images.githubusercontent.com/31029148/74879437-24242a00-538f-11ea-8098-5ca2531e4303.png)

Just open the server controller and it will look like this. We can see the url mapping that we have mentioned in our springboot application.

![Screenshot from 2020-02-20 03-15-49](https://user-images.githubusercontent.com/31029148/74879612-7feeb300-538f-11ea-8448-10540c35396b.png)


## Request Results on swagger

### Get All
  Click on get and then click on try out and then press execute. We will get all the objects stored in mongo database.
  
  ![Screenshot from 2020-02-20 03-19-07](https://user-images.githubusercontent.com/31029148/74879745-cfcd7a00-538f-11ea-862e-36b8a19ad27c.png)

### Get By Id

![Screenshot from 2020-02-20 03-21-39](https://user-images.githubusercontent.com/31029148/74879910-276be580-5390-11ea-8da7-e87a2578b6fb.png)

### Post

![Screenshot from 2020-02-20 03-25-34](https://user-images.githubusercontent.com/31029148/74880229-c395ec80-5390-11ea-8fe9-3fa36d2d23ea.png)

![Screenshot from 2020-02-20 03-25-59](https://user-images.githubusercontent.com/31029148/74880235-c7c20a00-5390-11ea-8596-da081be8b8d4.png)

### Delete By Id

![Screenshot from 2020-02-20 03-29-20](https://user-images.githubusercontent.com/31029148/74880446-41f28e80-5391-11ea-88a0-0d197747af34.png)

![Screenshot from 2020-02-20 03-29-40](https://user-images.githubusercontent.com/31029148/74880454-461eac00-5391-11ea-9e57-275e4baf955f.png)


### Get By Name

![Screenshot from 2020-02-20 03-27-58](https://user-images.githubusercontent.com/31029148/74880347-0788f180-5391-11ea-80fe-7b0bab5d1e66.png)

## Thank You!


