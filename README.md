# BlazorMicroserviciosPostgreSQL_IMPORTANTE

## How to run the application

1. Run this command to create the ContentPlatform.Api docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-api:latest -f ContentPlatform.Api/Dockerfile .
```

2. Confirm the image was created:

```
docker images
```

3. Login Docker Hub with this command:

```
docker login
```

4. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-api:latest
```

5.  Run this command to create the ContentPlatform.Reporting.Api docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-reporting-api:latest -f ContentPlatform.Reporting.Api/Dockerfile .
```

6. Confirm the image was created:

```
docker images
```

7. Login Docker Hub with this command:

```
docker login
```

8. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-reporting-api:latest
```

9. Run this command to create the contentplatform-ui docker image:

```
PS C:\14. Blazor LCE Youtube channel\BlazorMicroserviciosPostgreSQL_IMPORTANTE> docker build -t luiscoco/contentplatform-ui:latest -f ContentPlatform.Presentation/Dockerfile .
```

10. Confirm the image was created:

```
docker images
```

11. Login Docker Hub with this command:

```
docker login
```

12. Push the docker image into the Docker Hub:

```
docker push luiscoco/contentplatform-ui:latest
```

13. Press the "Docker-Compose" button in Visual Studio 2022

See the application output

![image](https://github.com/user-attachments/assets/4697bff1-e05d-4baa-9ba2-f891f365b337)

![image](https://github.com/user-attachments/assets/cff8bb33-643a-4840-8eaa-aeac03844608)

![image](https://github.com/user-attachments/assets/8109788f-7f27-4c06-b400-35a7df7c034b)

![image](https://github.com/user-attachments/assets/e96b5399-3b31-412d-9252-fc3f235f55e5)

![image](https://github.com/user-attachments/assets/0f659174-28b6-468c-b9df-21ded183346e)

![image](https://github.com/user-attachments/assets/0e584cca-2b92-4743-8a20-e046d2247d71)

![image](https://github.com/user-attachments/assets/84b16f15-bc44-4f74-8ae6-e82b8faa9a72)

![image](https://github.com/user-attachments/assets/77f10d00-cb81-4646-85cd-95762fcc971a)


