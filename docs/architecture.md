## Product Choise 
Yandex Go
https://taxi.yandex.ru/ru_ru/
application where you can order a taxi
## Main components
![Yandex-go Component Diagram](diagrams/out/yandex-go/architecture-component/Component%20Diagram.svg)
![Yandex-go Component Diagram Code](diagrams/src/yandex-go/architecture-component.puml)
"REST API" "YQL" "Payment Processing" "Events" "Maps API"
one two three four five
## Data flow
![Yandex-go Sequence Diagram.svg](diagrams/out/yandex-go/architecture-sequence/Sequence%20Diagram.svg)
![Yandex-go PlantUML sequence diagram](diagrams/src/yandex-go/architecture-sequence.puml)
Completion & Payment
something something
DispatchSvc -> PaySvc, PaySvc -> DB, and so on
## Deployment
![Yandex-go Deployment](diagrams/out/yandex-go/architecture-deployment/Deployment%20Diagram.svg)
![Yandex-go PlantUML](diagrams/src/yandex-go/architecture-deployment.puml)
for example
## Assumptions
Yandex Go: "I assume the pricing service handles surge pricing calculations based on demand and supply in real-time."
## Open questions
Yandex Go: "How does the actual load balancing mechanism work between the microservices in production?"