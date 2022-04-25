# voice_to_text
Voice to text using microsoft speech recognition library
This is a Visual Studio project to convert voice file (.wac) to text and prints this text on Console.

Code is in file /VoiceToTextDLL/VoiceToTextDLL/Class1.cs

Brief explanation of code:
Main is the entry point of the file, which calls the async function to recognize speech.

Line 22: The token is generated using Azure's console. 
Voice to text is a premium service and may require paid subscription: https://azure.microsoft.com/en-us/pricing/details/cognitive-services/speech-services/

Line 28: heart of the code which does the conversion using Microsoft's SDK.

Remaining lines print the result or error on the console.
