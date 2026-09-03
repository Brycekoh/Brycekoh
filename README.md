# hey, i'm bryce

final-year computing science (honours) student at UTS in sydney. i build backend systems, and i'm working my way into applied AI.

currently a software development intern at aubot. open to 2027 software engineering internships in sydney and singapore.

---

## what i'm building right now

an llm chatbot in python. streaming over the openai api, sqlite-backed conversation history, token accounting per turn. i'm writing each layer by hand instead of reaching for a framework, so when i do pick up langchain i'll know exactly what it's doing for me. retrieval is next.

eontree — react, vite and tailwind for a smart home installation business. real client, real deadline, no template.

## things i've built

### [patient-management](https://github.com/Brycekoh/patient-management)
three spring boot services that talk to each other two different ways on purpose: grpc when billing needs an answer before the request can continue, kafka when analytics just needs to know something happened. the second one is the interesting half, because it means reporting can fall over without taking patient records with it.

the readme has the architecture, the sequence diagrams, the event schemas and curl commands that work.

java · spring boot · kafka · grpc · protobuf · docker · postgresql · aws

### [grocery-store](https://github.com/Brycekoh/grocery-store)
django e-commerce with per-store inventory and store-scoped carts, so staff only ever see the store they're assigned to. finds your nearest store from a postcode with the haversine formula, geocoding coordinates on save rather than on every lookup. azure pipelines build, gated by 15 tests.

python · django · bootstrap · azure

### [adversarial_examples](https://github.com/Brycekoh/adversarial_examples)
i-fgsm against a pretrained resnet50 and a small cnn until both are wrong 100% of the time, then a purification defense that adapts the ddpm cosine-squared noise schedule and needs no auxiliary network to run. it disrupted 80% of attacks where the best classical defense managed 40%.

python · pytorch · numpy · cuda

## tech

languages — java, python, typescript, javascript, c++, swift, sql

backend — spring boot, django, kafka, grpc, protobuf, rest, postgresql, sqlite

infra — docker, aws (ecs, rds, msk), azure (app service, pipelines), ci/cd, git

learning — fastapi, retrieval-augmented generation, agent systems

## elsewhere

[email](mailto:Brycekoh420@gmail.com)
