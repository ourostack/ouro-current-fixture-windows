# Ouro Current fixture: Windows

A test repository for [Ouro Current](https://ui.ouroboros.bot/current/). It pins [Ouro UI for Windows](https://github.com/ourostack/ouro-ui-windows) through NuGet `PackageReference`s at an old release, so each new release shows up here as one Ouro Current pull request. Nothing here is built or shipped.

- `src/FixtureApp/FixtureApp.csproj`: `Ouro.UI.Windows` and `Ouro.Actions`.
- `src/FixtureApp/packages.lock.json`: a NuGet lock file, which Ouro Current names in its pull request instead of writing.
