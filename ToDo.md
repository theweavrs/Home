# ToDo

## Website
Improving the API documentation website hosted at https://github.com/ManagedBass/ManagedBass.DocFX

- Add Gitter Sidecar. Problem: Sidecar appears below the header, footer and floating buttons. Maybe something to do with `z-index`.
- Add more examples ported from BASS documentation.
- Add more valid parameters documentation. e.g. Flags.

## NuGet Package Improvements
These are some changes intended to be made to the NuGet package.
These are quite time consuming tasks and may not complete soon.

- Split NuGet package according to AddOns.
- Automate downloading of native libraries and installation in NuGet package.
  See https://github.com/ManagedBass/ManagedBass.NuGet for examples.
- Find way to DllMap on Xamarin.iOS so as to use a common PCL.

## Testing
Testing code is a never ending process, but ones to be done necesarily are mentioned below:

- Verify the [Xamarin.Android sample](https://github.com/ManagedBass/Demo.Xamarin.Android).