# PowerShell Script: Prothom Alo E-Paper to PDF Converter

[![Static Badge](https://img.shields.io/badge/Join%20Telegram%20Group-Readers%20Club-blue)](https://t.me/+jTKFvw-_SXg0NzZl)

## Description
This PowerShell script downloads images from [Prothom Alo ePaper](https://epaper.prothomalo.com/) website and converts them into a PDF file using ImageMagick.

## Requirements
- Windows OS
- PowerShell
- ImageMagick (Please download and install ImageMagick from [here](https://imagemagick.org/script/download.php#windows))

## Note
Open PowerShell/Terminal as Admin then run this `Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope CurrentUser` before running the script.

## Usage
1. Clone or download the script to your local machine.
2. Open PowerShell/Terminal and navigate to the directory containing the script.
3. Run the script by typing `.\run.ps1` and hitting Enter.

## How It Works
- Downloads website HTML source.
- Extracts image links from the HTML source.
- Downloads images from the extracted links.
- Converts downloaded images to a PDF file.

## File Structure
- `run.ps1`: The main PowerShell script file.
- `output/`: Folder where the generated PDF file is stored.
- `temp/`: Temporary folder where intermediate files are stored during script execution.

## Example
```powershell
.\run.ps1

