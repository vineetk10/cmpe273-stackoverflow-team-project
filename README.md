# cmpe273-stackoverflow-team-project

## Steps for backend setup:    

1. Clone the repo on your local machine
2. Change directory to the backend folder
3. Run npm install
4. Open the MySQL Client and create a database stackoverflow
5. Update the connection user and password to the SQL client in knexfile.js
6. Run npm start
    - This will create the user and tags table in your db.

## Database Schema:    

![Screen Shot 2022-08-30 at 2 34 45 PM](https://user-images.githubusercontent.com/26499781/187547724-59f3f94a-a2f0-4072-a824-a486bfdecff9.png)

## System Architecture Design

![Screen Shot 2022-08-30 at 2 37 02 PM](https://user-images.githubusercontent.com/26499781/187547968-4eb356d0-a115-436c-b184-659304756eda.png)

## Screen Captures

![Screen Shot 2022-08-30 at 2 43 54 PM](https://user-images.githubusercontent.com/26499781/187549086-05d9bb26-6618-4055-b09f-f44345126f93.png)

![Screen Shot 2022-08-30 at 2 45 39 PM](https://user-images.githubusercontent.com/26499781/187549340-f0904866-c290-4882-ae5e-a7e5a33846f5.png)

![Screen Shot 2022-08-30 at 2 49 27 PM](https://user-images.githubusercontent.com/26499781/187549862-be70128c-a000-470c-8ca9-171689a771b6.png)

![Screen Shot 2022-08-30 at 2 50 39 PM](https://user-images.githubusercontent.com/26499781/187550164-e37741a4-a3fc-4d83-b711-41bd1167f404.png)

![Screen Shot 2022-08-30 at 2 51 56 PM](https://user-images.githubusercontent.com/26499781/187550211-e61bd1dd-2062-490e-b648-a089121a3605.png)

![Screen Shot 2022-08-30 at 2 52 35 PM](https://user-images.githubusercontent.com/26499781/187550302-e2b0be5c-6ba1-431b-a9a7-b538b75e7733.png)

![Screen Shot 2022-08-30 at 2 53 24 PM](https://user-images.githubusercontent.com/26499781/187550450-95c96e0b-4326-4325-99ee-8739a388685e.png)

![Screen Shot 2022-08-30 at 2 54 05 PM](https://user-images.githubusercontent.com/26499781/187550542-9c0f4f8b-0bad-49d6-949a-44e8bbdc5d56.png)

## Performance Graphs

### JMeter Testing B (Base)

![Screen Shot 2022-08-30 at 2 58 02 PM](https://user-images.githubusercontent.com/26499781/187551084-11057d8c-1047-47d2-b092-a1e084bbb2c5.png)

![Screen Shot 2022-08-30 at 2 58 34 PM](https://user-images.githubusercontent.com/26499781/187551180-fbbc154c-d68d-4ffe-957b-aff078553313.png)

### JMeter Testing with connection pooling B+D

![Screen Shot 2022-08-30 at 2 59 37 PM](https://user-images.githubusercontent.com/26499781/187551281-bf0fcff1-10fd-4389-916b-7b164117ba60.png)

![Screen Shot 2022-08-30 at 3 00 14 PM](https://user-images.githubusercontent.com/26499781/187551352-b411d4a6-2010-40c2-be7c-b12f27f0748e.png)

### JMeter Testing with connection pooling and Redis (B + D + S)

![Screen Shot 2022-08-30 at 3 01 18 PM](https://user-images.githubusercontent.com/26499781/187551482-37f8e886-a368-4374-bb40-4ce829065053.png)

![Screen Shot 2022-08-30 at 3 01 52 PM](https://user-images.githubusercontent.com/26499781/187551552-e6cf3dc0-351b-4053-a061-37a32c844eb0.png)

### JMeter Testing with pooling, redis and Kafka (B + D + S + K)

![Screen Shot 2022-08-30 at 3 03 08 PM](https://user-images.githubusercontent.com/26499781/187551708-1d0ab6cc-eef3-49c6-ad8a-8dac04e6f85e.png)

![Screen Shot 2022-08-30 at 3 03 39 PM](https://user-images.githubusercontent.com/26499781/187551785-99b9fa84-4e35-4e61-b46e-5b0b21e9ea88.png)

### JMeter Testing - Overall Performance Comparison

![Screen Shot 2022-08-30 at 3 05 14 PM](https://user-images.githubusercontent.com/26499781/187551996-fa7ee231-584b-4f28-bc35-4319bcea1f28.png)

### Performance Comparison with Load Balancer

![Screen Shot 2022-08-30 at 3 06 05 PM](https://user-images.githubusercontent.com/26499781/187552121-e1d8f5d7-4bf8-4680-ae88-d71cb4fec5a3.png)


