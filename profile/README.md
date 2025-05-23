# AutoFixture

Write maintainable unit tests, faster.

AutoFixture makes it easier for developers to do Test-Driven Development by automating non-relevant Test Fixture Setup, allowing the Test Developer to focus on the essentials of each test case.

## Integrations

AutoFixture offers a variety of utility packages and integrations with most of the major mocking libraries and testing frameworks.

### Core packages

The core packages offer the full set of AutoFixture's features without requring any testing framework or third party integration.

| Product | Package | Stable | Preview | Downloads |
|---------|---------|--------|---------|-----------|
| The core package | [AutoFixture](http://www.nuget.org/packages/AutoFixture) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture)](https://www.nuget.org/packages/AutoFixture) | [![NuGet](https://img.shields.io/nuget/vpre/autofixture)](https://www.nuget.org/packages/AutoFixture) | ![NuGet](https://img.shields.io/nuget/dt/autofixture) |
| Assertion idioms | [AutoFixture.Idioms](http://www.nuget.org/packages/AutoFixture.Idioms) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.Idioms)](https://www.nuget.org/packages/AutoFixture.Idioms) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.Idioms)](https://www.nuget.org/packages/AutoFixture.Idioms) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.idioms) |
| Seed extensions | [AutoFixture.SeedExtensions](http://www.nuget.org/packages/AutoFixture.SeedExtensions) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.SeedExtensions)](https://www.nuget.org/packages/AutoFixture.SeedExtensions) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.SeedExtensions)](https://www.nuget.org/packages/AutoFixture.SeedExtensions) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.seedextensions) |

### Mocking libraries

AutoFixture offers integations with most major .NET mocking libraries.<br/>
These integrations enable such features as configuring mocks, auto-injecting mocks, etc.

| Product | Package | Stable | Preview | Downloads |
|---------|---------|--------|---------|-----------|
| Moq | [AutoFixture.AutoMoq](http://www.nuget.org/packages/AutoFixture.AutoMoq) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.AutoMoq)](https://www.nuget.org/packages/AutoFixture.AutoMoq) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.AutoMoq)](https://www.nuget.org/packages/AutoFixture.AutoMoq) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.automoq) |
| NSubstitute | [AutoFixture.AutoNSubstitute](http://www.nuget.org/packages/AutoFixture.AutoNSubstitute) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.AutoNSubstitute)](https://www.nuget.org/packages/AutoFixture.AutoNSubstitute) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.AutoNSubstitute)](https://www.nuget.org/packages/AutoFixture.AutoNSubstitute) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.AutoNSubstitute) |
| FakeItEasy | [AutoFixture.AutoFakeItEasy](http://www.nuget.org/packages/AutoFixture.AutoFakeItEasy) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.AutoFakeItEasy)](https://www.nuget.org/packages/AutoFixture.AutoFakeItEasy) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.AutoFakeItEasy)](https://www.nuget.org/packages/AutoFixture.AutoFakeItEasy) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.AutoFakeItEasy) |
| Rhino Mocks | [AutoFixture.AutoRhinoMocks](http://www.nuget.org/packages/AutoFixture.AutoRhinoMocks) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.AutoRhinoMocks)](https://www.nuget.org/packages/AutoFixture.AutoRhinoMocks) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.AutoRhinoMocks)](https://www.nuget.org/packages/AutoFixture.AutoRhinoMocks) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.AutoRhinoMocks) |

### Testing frameworks

AutoFixture offers integrations with most major .NET testing frameworks.<br />
These integrations enable auto-generation of test cases, combining auto-generated data with inline arguments, etc.

| Product | Package | Stable | Preview | Downloads |
|---------|---------|--------|---------|-----------|
| xUnit v3 | [AutoFixture.Xunit3](http://www.nuget.org/packages/AutoFixture.Xunit3) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.Xunit3)](https://www.nuget.org/packages/AutoFixture.Xunit3) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.Xunit3)](https://www.nuget.org/packages/AutoFixture.Xunit3) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.xUnit3) |
| xUnit v2 | [AutoFixture.Xunit2](http://www.nuget.org/packages/AutoFixture.Xunit2) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.Xunit2)](https://www.nuget.org/packages/AutoFixture.Xunit2) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.Xunit2)](https://www.nuget.org/packages/AutoFixture.Xunit2) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.xUnit2) |
| xUnit v1 | [AutoFixture.Xunit](http://www.nuget.org/packages/AutoFixture.Xunit) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.Xunit)](https://www.nuget.org/packages/AutoFixture.Xunit) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.Xunit)](https://www.nuget.org/packages/AutoFixture.Xunit) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.XUnit) |
| NUnit v4 | [AutoFixture.NUnit4](http://www.nuget.org/packages/AutoFixture.NUnit4) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.NUnit4)](https://www.nuget.org/packages/AutoFixture.NUnit4) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.NUnit4)](https://www.nuget.org/packages/AutoFixture.NUnit4) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.NUnit4) |
| NUnit v3 | [AutoFixture.NUnit3](http://www.nuget.org/packages/AutoFixture.NUnit3) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.NUnit3)](https://www.nuget.org/packages/AutoFixture.NUnit3) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.NUnit3)](https://www.nuget.org/packages/AutoFixture.NUnit3) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.NUnit3) |
| NUnit v2 | [AutoFixture.NUnit2](http://www.nuget.org/packages/AutoFixture.NUnit2) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.NUnit2)](https://www.nuget.org/packages/AutoFixture.NUnit2) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.NUnit2)](https://www.nuget.org/packages/AutoFixture.NUnit2) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.NUnit2) |
| Foq | [AutoFixture.AutoFoq](http://www.nuget.org/packages/AutoFixture.AutoFoq) | [![NuGet](https://img.shields.io/nuget/v/AutoFixture.AutoFoq)](https://www.nuget.org/packages/AutoFixture.AutoFoq) | [![NuGet](https://img.shields.io/nuget/vpre/AutoFixture.AutoFoq)](https://www.nuget.org/packages/AutoFixture.AutoFoq) | ![NuGet](https://img.shields.io/nuget/dt/autofixture.AutoFoq) |

You can check the compatibility with your target framework version on the [wiki](https://github.com/AutoFixture/AutoFixture/wiki#net-platforms-compatibility-table) or on the [NuGet](https://www.nuget.org/profiles/AutoFixture) website.

### .NET Foundation

This project is supported by the [.NET Foundation](https://dotnetfoundation.org).
