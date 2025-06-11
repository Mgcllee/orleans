# Orleans 소스 코드 분석

### Grain.cs

IGrainBase, IAddressable 인터페이스를 상속받아서 Grain 클래스를 선언.  
Grain<TGrainState> 는 Grain을 상속 받아서 구현함.

[Grain.cs 코드 위치](Orleans.Core.Abstractions/Core/Grain.cs)

<br/>

### Silo.cs

[Silo.cs 코드 위치](Orleans.Runtime/Silo/Silo.cs)

<br/>

| 이름 | 목적 | 설명 |
|---|---|---|
|AWS|||
|AdoNet|||
|Azure|||
|Cassandra/Orleans.Clustering.Cassandra|||
|Orleans.Analyzers|||
|Orleans.BroadcastChannel|||
|Orleans.Client|||
|Orleans.Clustering.Consul|||
|Orleans.Clustering.ZooKeeper|||
|Orleans.CodeGenerator|||
|Orleans.Connections.Security|||
|Orleans.Core.Abstractions|||
|Orleans.Core|||
|Orleans.EventSourcing|||
|Orleans.Hosting.Kubernetes|||
|Orleans.Journaling|||
|Orleans.Persistence.Memory|||
|Orleans.Reminders.Abstractions|||
|Orleans.Reminders|||
|Orleans.Runtime|||
|Orleans.Sdk|||
|Orleans.Serialization.Abstractions|||
|Orleans.Serialization.FSharp|||
|Orleans.Serialization.MessagePack|||
|Orleans.Serialization.NewtonsoftJson|||
|Orleans.Serialization.SystemTextJson|||
|Orleans.Serialization.TestKit|||
|Orleans.Serialization|||
|Orleans.Server|||
|Orleans.Streaming.Abstractions|||
|Orleans.Streaming|||
|Orleans.TestingHost|||
|Orleans.Transactions.TestKit.Base|||
|Orleans.Transactions.TestKit.xUnit|||
|Orleans.Transactions|||
|Redis|||
|Serializers/Orleans.Serialization.Protobuf|||
|api|||
|Directory.Build.props|||
Directory.Build.targets|||
