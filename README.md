# CoreTestRepo

***Notes:***

1)gRPC Client on ASP.NET Core app


    <Project Sdk="Microsoft.NET.Sdk.Web">
    
      <PropertyGroup>
        <TargetFramework>net5.0</TargetFramework>
      </PropertyGroup>
    
      <ItemGroup>
        <Protobuf Include="Protos\greet.proto" GrpcServices="Client" />
      </ItemGroup>
      
      <ItemGroup>
        <PackageReference Include="Google.Protobuf" Version="3.16.0" />
        <PackageReference Include="Grpc.Net.Client" Version="2.37.0" />
        <PackageReference Include="Grpc.Tools" Version="2.37.1">
          <PrivateAssets>all</PrivateAssets>
          <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
        </PackageReference>
        <PackageReference Include="Microsoft.VisualStudio.Web.CodeGeneration.Design" Version="5.0.2" />
      </ItemGroup>
    </Project>

