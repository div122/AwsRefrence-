![image](https://user-images.githubusercontent.com/25984260/188676756-62ccea21-d376-49d1-b02c-6fe28206f568.png)
![image](https://user-images.githubusercontent.com/25984260/188692966-0adee317-4dde-4f77-8a67-2a7eb4b61770.png)
![image](https://user-images.githubusercontent.com/25984260/188756783-bcdd528e-30c7-4465-b0ea-e02aefebb06b.png)
![image](https://user-images.githubusercontent.com/25984260/188756820-e28e976f-c4a1-4149-aa76-aae970ac391e.png)
![image](https://user-images.githubusercontent.com/25984260/188756856-dcf29047-1bf8-42c7-acfc-a90ccf6dcf5f.png)
![image](https://user-images.githubusercontent.com/25984260/188757065-a115676d-166b-4eda-9f45-aad7e7ff07f7.png)
![image](https://user-images.githubusercontent.com/25984260/188757194-5fc0ea26-e7bd-449a-bec1-bed423e8decd.png)
![image](https://user-images.githubusercontent.com/25984260/188757296-e7d55c4f-5d57-4d74-8d77-6044a211cc86.png)
![image](https://user-images.githubusercontent.com/25984260/188757426-10f3fd61-b2b2-44a3-bead-8d71d2ea24dc.png)
![image](https://user-images.githubusercontent.com/25984260/188757481-cd0d073e-a213-404b-b51d-33ed44eceb2f.png)
![image](https://user-images.githubusercontent.com/25984260/188757532-dfc612e7-505c-4565-9459-e34f42a0db9f.png)
![image](https://user-images.githubusercontent.com/25984260/188757562-6d7255fa-6691-4033-a79d-2e48bd25ad5c.png)
![image](https://user-images.githubusercontent.com/25984260/188757780-6be74a67-169f-4ae3-80cf-b02f26d91651.png)
![image](https://user-images.githubusercontent.com/25984260/188757921-9a730c4f-7b60-4f56-9c6a-a1dd47fa1af8.png)
![image](https://user-images.githubusercontent.com/25984260/188758014-155a75b5-c944-40c0-b403-714051caf11b.png)
![image](https://user-images.githubusercontent.com/25984260/188758082-4fda4d38-d0f3-4e17-8e4c-4d7e9f62a820.png)
![image](https://user-images.githubusercontent.com/25984260/188758158-76f8e66c-dcf9-4c13-8ce0-29bd117ad52a.png)
![image](https://user-images.githubusercontent.com/25984260/188758241-235a458b-08bd-44d5-9141-a57e184bc536.png)
![image](https://user-images.githubusercontent.com/25984260/188758289-8dbecdd7-fc1f-4c09-b629-3fdb207451c8.png)

By using ECS we will deploy containers . Task Definition is the place where we will put the all info about container.

Here we can able to see task definition.Each time you modify a task definition  new revision will be created for that specific version.

![image](https://user-images.githubusercontent.com/25984260/188758466-30a23beb-5036-4ab0-ae4c-87a322712fbb.png)
![image](https://user-images.githubusercontent.com/25984260/188758509-3ff4b769-da9b-49cf-9ce5-4e7abdd131ee.png)
![image](https://user-images.githubusercontent.com/25984260/188758533-7222e6ad-809b-4119-abf3-85045a9a4f9e.png)
![image](https://user-images.githubusercontent.com/25984260/188758748-73e36be4-72d5-4451-8d72-b386508e05f6.png)
![image](https://user-images.githubusercontent.com/25984260/188758795-ef1b1888-b0a7-49aa-a1c0-2248ebb5be75.png)
![image](https://user-images.githubusercontent.com/25984260/188758834-9e849315-f03b-4ee8-8da9-1be7fc2d0a3c.png)
![image](https://user-images.githubusercontent.com/25984260/188758869-0cd5c33f-b55b-431e-a2ed-32169de455c6.png)
![image](https://user-images.githubusercontent.com/25984260/188758934-e8d583d4-df2b-4c2e-abab-96c0c7297519.png)
![image](https://user-images.githubusercontent.com/25984260/188759414-82b4e722-d7af-4bd2-8127-6e347256a931.png)
![image](https://user-images.githubusercontent.com/25984260/188759459-f089145d-7cb1-4620-80ca-9c88e06b3e10.png)

![image](https://user-images.githubusercontent.com/25984260/188759570-274fce45-c3e1-4298-b338-5537a06bad4e.png)
![image](https://user-images.githubusercontent.com/25984260/188759597-1fa54578-b5a4-4994-945f-fe66c78f3e24.png)
![image](https://user-images.githubusercontent.com/25984260/188759617-1dc5dfb9-f685-4b9d-bcba-581432bb212b.png)
![image](https://user-images.githubusercontent.com/25984260/188759663-3888f03c-bca6-4920-b320-6dc34c5b8eab.png)
![image](https://user-images.githubusercontent.com/25984260/188759698-4b75d60f-d377-44fd-bd20-90342c290233.png)
![image](https://user-images.githubusercontent.com/25984260/188759726-758d5246-cf7e-4757-827b-aa579d7dedfe.png)


Memory limits:
      1.soft limit: How much memory reserve for container.
      2.Hard limit :Maximum amount of memory this container can use. If that limit exceed container will be killed.
      
![image](https://user-images.githubusercontent.com/25984260/188759892-93bb3d24-8705-416a-b8c1-183a670dffef.png)
![image](https://user-images.githubusercontent.com/25984260/188759977-21a5c7ca-4f1a-4186-a704-188e2145f36a.png)
![image](https://user-images.githubusercontent.com/25984260/188760097-466e8142-0121-448d-953e-f85f4e855c70.png)
![image](https://user-images.githubusercontent.com/25984260/188760122-50ae047d-5822-4073-8ab2-211cacef82d0.png)

https://docs.aws.amazon.com/eks/latest/userguide/service_IAM_role.html#create-service-role
![image](https://user-images.githubusercontent.com/25984260/188760244-d0a99d81-b91c-48ba-abdf-25cd91f1780d.png)
![image](https://user-images.githubusercontent.com/25984260/188760306-be7197ed-96a5-47f5-9131-d07f87bcb28e.png)
![image](https://user-images.githubusercontent.com/25984260/188760450-beb16f85-5b58-4187-be92-25ac38e79238.png)
![image](https://user-images.githubusercontent.com/25984260/188760503-44fb43b1-9b9c-456d-ba39-192901ac28cc.png)
![image](https://user-images.githubusercontent.com/25984260/188760525-864fab7b-4310-4295-a415-73728e327d0d.png)
![image](https://user-images.githubusercontent.com/25984260/188760592-44fd321b-b93f-435b-ad13-3845e2665daf.png)
![image](https://user-images.githubusercontent.com/25984260/188760672-df047158-6462-46b3-88c5-3cb9bd9a3081.png)
![image](https://user-images.githubusercontent.com/25984260/188760726-55988787-cdf5-4386-9a07-0a69d1f15a93.png)
![image](https://user-images.githubusercontent.com/25984260/188760762-6672bc5c-d343-4bf0-b603-d1623619f9cd.png)
![image](https://user-images.githubusercontent.com/25984260/188760853-210fae67-d15f-4911-9427-75f23a47a0eb.png)
![image](https://user-images.githubusercontent.com/25984260/188760883-96e3a8c7-ab0a-42a8-9792-a7a69fdb4370.png)
![image](https://user-images.githubusercontent.com/25984260/188761076-6894d09b-8a07-4171-9878-892606bdc145.png)
![image](https://user-images.githubusercontent.com/25984260/188761144-5a16a2e7-ae10-485c-a519-f4ae4de227c4.png)
![image](https://user-images.githubusercontent.com/25984260/188761209-ad4dfcb3-56f5-4ca9-9bd0-644ddffeb07c.png)
![image](https://user-images.githubusercontent.com/25984260/188761240-1b61b7c5-840f-42af-a650-bdf281660530.png)
![image](https://user-images.githubusercontent.com/25984260/188761268-bc7d4925-1624-4d55-9d7e-1aed19e4299d.png)
![image](https://user-images.githubusercontent.com/25984260/188761298-05fb7dc9-2c23-48b3-80cc-148e3b3c483a.png)
![image](https://user-images.githubusercontent.com/25984260/188761356-0f934eb7-e09e-4470-8f5c-5dbf0ff2699f.png)

