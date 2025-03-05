# Console API Call

#### _A console app that displays the current Top Stories on the New York Times._

#### By _**India Lyon-Myrick**_

## Technologies Used

* _C#_
* _.NET_
* _Git_

## Description

_A console app made for practice with API calls that displays the current top stories from the New York Times._

## Setup/Installation Requirements

* _You will need [.NET](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) and [Git](https://git-scm.com/downloads/) in order to run the program._

_1: Clone the repository to a folder of choice on your machine (by either using the "Code" button on the GitHub page, or in a terminal application using `git clone https://github.com/igl-myrick/ConsoleApiCall`)._

_2: Using a terminal application such as Git Bash or Windows Command Prompt, navigate to the `ConsoleApiCall` folder._

_3. You will need to register an API key on the [New York Times' website](https://developer.nytimes.com/)._

_4: Once you have an API key, create an `EnvironmentVariables.cs` file within the `ConsoleApiCall` folder, including the following code:_

```
namespace ConsoleApiCall.Keys
{
  public static class EnvironmentVariables
  {
    public static string ApiKey = "[YOUR-API-KEY-HERE]";
  }
}
```

_Insert your own API key in place of [YOUR-API-KEY-HERE]._

_5: Next, run `dotnet build` in the command line to build the program._

_6: Once the program is built, run `dotnet run` to run the program and view current stories._

## Known Bugs

* _None at the moment_

## License

MIT:

Copyright (c) _3/3/2025_ _India Lyon-Myrick_

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.