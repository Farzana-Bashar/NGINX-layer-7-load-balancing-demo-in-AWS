# deploy-simple-nodejs-app-on-AWS-using-nginx

<img width="800" alt="1-vpc" src="https://user-images.githubusercontent.com/76453366/118481683-8ce68780-b735-11eb-93af-a165a2240dd5.png">

<img width="800" alt="2-vpc" src="https://user-images.githubusercontent.com/76453366/118482045-07afa280-b736-11eb-9d60-abb350feb9cf.png">

<img width="800" alt="3-igw" src="https://user-images.githubusercontent.com/76453366/118482125-201fbd00-b736-11eb-8ceb-098dffcdf009.png">

<img width="800" alt="4-igw-attatch" src="https://user-images.githubusercontent.com/76453366/118482758-ff0b9c00-b736-11eb-8210-91994da970d9.png">

<img width="800" alt="5-igw-attatch" src="https://user-images.githubusercontent.com/76453366/118482816-134f9900-b737-11eb-997e-1736ee4ac675.png">

<img width="800" alt="6-igw--attatched" src="https://user-images.githubusercontent.com/76453366/118483466-db952100-b737-11eb-8d7c-4a2e23d71f23.png">

<img width="800" alt="7-subnet" src="https://user-images.githubusercontent.com/76453366/118483533-ef408780-b737-11eb-89c5-2371d1dca123.png">

<img width="800" alt="8-subnet" src="https://user-images.githubusercontent.com/76453366/118483587-fff0fd80-b737-11eb-947d-9bd833487789.png">

<img width="800" alt="9-ec2" src="https://user-images.githubusercontent.com/76453366/118483649-10a17380-b738-11eb-98cb-0dd90cc75948.png">

<img width="800" alt="10-ec2" src="https://user-images.githubusercontent.com/76453366/118483681-20b95300-b738-11eb-9dce-2b3f10135209.png">

<img width="800" alt="11-ec2" src="https://user-images.githubusercontent.com/76453366/118483735-33338c80-b738-11eb-8df2-1430250aedac.png">

<img width="800" alt="12-ec2" src="https://user-images.githubusercontent.com/76453366/118483778-421a3f00-b738-11eb-91d4-f8850045fe86.png">

<img width="800" alt="13-ec2" src="https://user-images.githubusercontent.com/76453366/118483831-52cab500-b738-11eb-9f1c-a06a453a54a7.png">

<img width="800" alt="14-ec2" src="https://user-images.githubusercontent.com/76453366/118483891-64ac5800-b738-11eb-932d-d6d9d0829c83.png">

<img width="800" alt="15-ec2" src="https://user-images.githubusercontent.com/76453366/118483925-72fa7400-b738-11eb-922b-1830c19f4398.png">

<img width="800" alt="16-ec2" src="https://user-images.githubusercontent.com/76453366/118483976-84438080-b738-11eb-9975-0d35e82a9ccc.png">

<img width="800" alt="17-ec2-launched" src="https://user-images.githubusercontent.com/76453366/118484017-91f90600-b738-11eb-985f-68d7f97594b2.png">

<img width="800" alt="18-ec2-key" src="https://user-images.githubusercontent.com/76453366/118484997-aee20900-b739-11eb-9ecb-ced58eb630d4.png">

<img width="800" alt="19-new-ec2-launched" src="https://user-images.githubusercontent.com/76453366/118485062-bc978e80-b739-11eb-9416-2fb7c2003baf.png">

<img width="800" alt="20-new-ec2-launched" src="https://user-images.githubusercontent.com/76453366/118485285-0c765580-b73a-11eb-87b4-415acb06278f.png">

<img width="800" alt="21-route-table" src="https://user-images.githubusercontent.com/76453366/118485326-1c8e3500-b73a-11eb-9342-6339beb02d64.png">

<img width="800" alt="22-route-table-created" src="https://user-images.githubusercontent.com/76453366/118485373-2b74e780-b73a-11eb-8e12-66a0c8cda2ee.png">

<img width="800" alt="23-routetable-rules" src="https://user-images.githubusercontent.com/76453366/118485507-58c19580-b73a-11eb-93eb-e11f945fc9f1.png">

<img width="800" alt="24-routetable-rules" src="https://user-images.githubusercontent.com/76453366/118485574-6d9e2900-b73a-11eb-94b7-58f6f839dfac.png">

<img width="800" alt="25-routetable-rules" src="https://user-images.githubusercontent.com/76453366/118485649-80b0f900-b73a-11eb-8acd-864c641d83f9.png">

<img width="800" alt="26-nginx-vm" src="https://user-images.githubusercontent.com/76453366/118485765-9faf8b00-b73a-11eb-9d94-2dcf43c94fda.png">

<img width="800" alt="27-sg-new-rules" src="https://user-images.githubusercontent.com/76453366/118485896-ca99df00-b73a-11eb-884d-0167e2a60465.png">

<img width="800" alt="28-vm1" src="https://user-images.githubusercontent.com/76453366/118485946-d8e7fb00-b73a-11eb-8a39-1ab557a18993.png">

<img width="800" alt="29-output-vm1" src="https://user-images.githubusercontent.com/76453366/118485995-e9987100-b73a-11eb-8846-0eef47091183.png">

<img width="800" alt="30-output-vm2" src="https://user-images.githubusercontent.com/76453366/118486036-f6b56000-b73a-11eb-9f06-3ec5d1be4e98.png">

<img width="800" alt="31-sg-new-rules-nginx" src="https://user-images.githubusercontent.com/76453366/118486185-206e8700-b73b-11eb-9d7b-c2f2944f868b.png">

<img width="800" alt="32-output-nginx-port80" src="https://user-images.githubusercontent.com/76453366/118486253-38460b00-b73b-11eb-8a89-783922e0f925.png">

<img width="800" alt="33-new-sg for vm1 2" src="https://user-images.githubusercontent.com/76453366/118486373-56137000-b73b-11eb-859d-75ab45506159.png">

<img width="800" alt="34-new-sg for vm1 2" src="https://user-images.githubusercontent.com/76453366/118486459-77745c00-b73b-11eb-8ffd-d7989d18ecd7.png">

<img width="800" alt="35-attatch-sg-to-vm1 2" src="https://user-images.githubusercontent.com/76453366/118486514-88bd6880-b73b-11eb-99dc-ddf277ac486b.png">

<img width="800" alt="36-attatch-sg-to-vm1 2" src="https://user-images.githubusercontent.com/76453366/118486578-97a41b00-b73b-11eb-99b7-ef6ae2268c8a.png">

<img width="800" alt="37-attatch-sg-to-vm1 2" src="https://user-images.githubusercontent.com/76453366/118486648-aab6eb00-b73b-11eb-9bec-ea9c54ecbf51.png">

<img width="800" alt="38-attatch-sg-to-vm1 2" src="https://user-images.githubusercontent.com/76453366/118486693-b99d9d80-b73b-11eb-9f99-78f5b0d67641.png">

<img width="800" alt="39-attatch-sg-to-vm1 2" src="https://user-images.githubusercontent.com/76453366/118486758-cae6aa00-b73b-11eb-9055-534716dfb4c6.png">

<img width="800" alt="40-final-output" src="https://user-images.githubusercontent.com/76453366/118486821-dc2fb680-b73b-11eb-8a9b-1f6e2fa9c988.png">


