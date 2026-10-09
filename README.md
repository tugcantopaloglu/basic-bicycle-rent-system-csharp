# Bicycle Rental Data Structures Demo

A C# console exercise for organizing bicycle stations and sample customers with a binary tree, a hash table, heap operations, and sorting helpers. Station data is embedded in `Program.cs` and customer data is generated randomly. The source and console prompts retain the original Turkish course terminology.

This checkout contains a console demonstration. It has no website, payment flow, customer login, administrator dashboard, or persistent rental database.

## Build and run

Use the .NET 8 SDK or a compatible newer SDK and run from the repository root:

```sh
dotnet build BicycleRentDemo.csproj --configuration Release
dotnet run --project BicycleRentDemo.csproj --configuration Release --no-build
```

Use an interactive terminal for the original console prompts and the final keypress. Randomly generated customers can produce different output across runs.

## Source layout

- `Program.cs`: station fixtures, generated customers, and demonstration flow.
- `Durak.cs` and `DurakAgaci.cs`: station representation and binary tree.
- `Musteri.cs`: sample rental customer data.
- `QuickSort.cs` and other helper files: sorting and heap demonstrations.

The project file builds the existing C# files without changing the exercise's types. There are no external packages or network services. Local build and sample execution do not establish inventory correctness or production rental behavior.

## Repository

The source repository is [basic-bicycle-rent-system-csharp](https://github.com/tugcantopaloglu/basic-bicycle-rent-system-csharp). No root license file is present in this checkout; the previous README's MIT license claim was not supported by a committed license file.
