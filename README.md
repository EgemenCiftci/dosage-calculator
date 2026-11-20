# Dosage Calculator

A responsive Blazor WebAssembly app for weight-based ibuprofen and paracetamol dosage calculations.

## Features

- Ibuprofen and paracetamol calculators with maximum single and daily dose estimates
- Weight input in kilograms with quick-select options
- Administration interval reminders and medical-use disclaimers
- Responsive layout for desktop and mobile
- Client-side routing and production service-worker support

## Run locally

Requires the .NET 11 SDK.

From the repository root, run the HTTP development profile:

```sh
dotnet run --project DosageCalculator/DosageCalculator.csproj --launch-profile http
```

Alternatively, open `DosageCalculator.sln` in Visual Studio and run the `http` launch profile.

## Medical disclaimer

This application provides general information only. Its calculations are not a substitute for the product label, a clinician's instructions, or advice from a qualified healthcare professional. Confirm the appropriate medication and dose with a healthcare professional before use.
