Issues I faces in this lab:
I put the whole folder, rather than the separate files in the repo causing the CI actions to fail.

Provided the GCP project name instead of project ID in the Github Secrets, causing CD actions to fail.

Was not using entire JSON payload in the github secrets GCP key, only the key value. This caused the CD actions to fail

Did not provide the appropriate permissions for service account. With link provided by class mate fixed: https://serverfault.com/questions/1044638/sudden-permissions-denied-for-service-account

Otherwise all steps were followed as described in the lab assignment, in class, and previous class recording provided by Professor Nguyen.

Screenshots:


CI Workflow Process:
<img width="1440" alt="1" src="https://user-images.githubusercontent.com/62492189/168415668-bdbb7ec5-4110-425b-ad80-c03f6adaf3aa.png">
<img width="1440" alt="2" src="https://user-images.githubusercontent.com/62492189/168415676-a8d7c773-eb64-41b3-81e4-934937a49007.png">

CD Workflow Process:
<img width="1440" alt="service_account" src="https://user-images.githubusercontent.com/62492189/168415710-4bbaa2e1-7ac4-4107-a6d6-9d112bf61617.png">
<img width="1440" alt="key" src="https://user-images.githubusercontent.com/62492189/168415697-92944aab-85d1-4f8c-a004-10dfa33449d5.png">
<img width="1440" alt="secrets" src="https://user-images.githubusercontent.com/62492189/168415718-a1ff8fc0-bc81-41fa-beb3-e0119a575d90.png">
<img width="1440" alt="yml" src="https://user-images.githubusercontent.com/62492189/168415749-6c38b32a-1669-4dbe-802c-0e067f442b00.png">
<img width="1440" alt="creating release" src="https://user-images.githubusercontent.com/62492189/168416088-39e989a9-ab80-43bd-b661-c7556205cf7d.png">
<img width="1440" alt="release" src="https://user-images.githubusercontent.com/62492189/168415725-85b80113-5a47-4812-ad4a-e0aad7d280cf.png">
<img width="1440" alt="pushed_release" src="https://user-images.githubusercontent.com/62492189/168416150-a63c297a-4978-41ec-83d3-6ca330c91def.png">
<img width="1440" alt="deploying" src="https://user-images.githubusercontent.com/62492189/168416151-269fe454-fe11-4bb9-a19d-830e9473ee19.png">
<img width="1440" alt="deployed_run" src="https://user-images.githubusercontent.com/62492189/168415729-ea685dfd-f445-4418-a8ad-b66d78356294.png">
<img width="1440" alt="workflow" src="https://user-images.githubusercontent.com/62492189/168415768-210f06cc-3637-4001-a8d3-b9a9011f9981.png">


GCP Console showing working deployment:
<img width="1440" alt="cluster" src="https://user-images.githubusercontent.com/62492189/168415761-fbd52984-6b99-4928-9704-801a6281f547.png">
<img width="1440" alt="workload" src="https://user-images.githubusercontent.com/62492189/168415770-af5d7268-e1aa-40cd-a509-025976b92676.png">
<img width="1440" alt="services" src="https://user-images.githubusercontent.com/62492189/168415771-dd7eb297-ddf3-41d8-8263-91964505af22.png">

Creation of and working ingress:
<img width="1440" alt="c_ingress" src="https://user-images.githubusercontent.com/62492189/168415775-f449ff78-be48-47d0-8c74-dfdef39d75c7.png">
<img width="1440" alt="ingress" src="https://user-images.githubusercontent.com/62492189/168415776-a7d1dbfb-5371-47ef-aee5-cf5f7251e0eb.png">

Working Gumball:
<img width="1440" alt="gumball" src="https://user-images.githubusercontent.com/62492189/168415788-9ba2efa2-8f9d-4734-b2ce-c4d7d58d47c9.png">
