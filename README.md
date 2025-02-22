# Icod.Prefix
Prefix.exe prepends the specified string to the head of the specified file.

## Usage
`Prefix.exe (-h | --help | /help)`
Displays this text.

`Prefix.exe (-c | --copyright | /copyright)`
Displays copyright and licensing information.

`Prefix.exe (-p | --prefix | /prefix) thePrefix [(-i | --input | /input) inputFilePathName] [(-o | --output | /output) outputFilePathName] [(-t | --trim | /trim)]`
Prefix.exe prefixes each line of input with the specified string.
inputFilePathName and outputFilePathName may be relative or absolute paths.
If inputFilePathName is omitted then input is read from StdIn.
If outputFilePathName is omitted then output is written to StdOut.
If trim switch is specified, then input lines are trimmed of all surrounding whitespace and empty lines are ignored.

## Copyright and Licensing
Prefix.exe prepends the specified string to the head of the specified file.
Copyright( C ) 2025 Timothy J. Bruce

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published 
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

