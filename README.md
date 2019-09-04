# BuildExtensions.DeterministicPdb
Creates deterministic assembly and pdb not depend to project location

## Usage
Avoids to include your project location full path into an assembly and a pdb.

Only to do install this package.

```csproj
<ItemGroup>
  <PackageReference Include="BuildExtensions.DeterministicPdb" Version="1.0.0" PrivateAssets="All" />
</ItemGroup>
```

## License
MIT
