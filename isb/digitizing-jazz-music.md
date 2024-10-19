# Digitizing Jazz Band Music

## Goal

The ISB seeks to inventory the existing file cabinets full of Jazz band music. At present no information is known about any of the pieces of music, other than that these physical file cabinets contain jazz band music.

## Proposed Solution

A phased divide and conquer approach can be used to digitize the inventory from these physical file cabinets.

The benefits of this approach minimize the time commitment of any one individual while making a big impact toward inventorying this music.

### Phase 1: Creating Labeled Folders

The first phase will involve Gary creating several hundred pre-labeled folders with the target inventory locations on them. These will be of the form J-XXX, where "XXX" is a 3 digit number indicating the inventory location. E.g., "J-001", "J-002", ..., "J-999".

### Phase 2: Taking Pictures of the Music

A team of volunteers will be recruited on a specific "work day" to take pictures of the music in each of the file cabinets. A volunteer will be given a stack of music, and a stack of pre-labeled folders. Using their smart phone, the volunteer will take a picture of the piece of music **including the inventory number** from the pre-labeled folder. Each piece of music will be placed in the appropriate pre-labeled folder, and filed in the appropriate file cabinet.

At the end of the volunteer day, the pictures will either be Airdropped from an iOS user to James Alexander, or uploaded from an Android user to a pre-shared public Google drive folder.

### Phase 3: Data Entry - OCR

From the pictures, James Alexander will create a spreadsheet with the following columns:

1. Inventory Number
2. Title
3. Composer
4. Arranger
5. Publisher

James will use tools like `keras-ocr` or `easy-ocr` to extract the text from the images. There will likely need to be some manual modification of the output to correct any errors. Depending on the number of errors, and number of images captured, this may or may not require additional volunteers.

### Phase 4: Data Entry - Manual (if necessary)

Once the spreadsheet is created, a team of volunteers will be recruited to manually enter the data into the ISB's inventory system. This will involve entering the data from the spreadsheet into the ISB's inventory system. The challenge here will be informing the volunteer which files have been input and which have not.

One option is to have the volunteers rename the file names of the images once they've been input into the spreadsheet. Or consider using an "Archive" folder that the image can be moved to upon entering into the spreadsheet.

## Challenges

1. The library location is in a closet of Warren Central high school. Because of the build materials of the room where the music is stored, the room is effectively a [Faraday cage](https://en.wikipedia.org/wiki/Faraday_cage). This means that there is no cell phone signal in the room. This will require the volunteers to leave the room to upload the images. This also restricts any use of cloud services from _within_ the room.

2. There is not a lot of room in the library itself. There is enough room for a few folding tables laid end to end, and 2 volunteers on each side, but not much more room than that. This will limit the number of volunteers that can be recruited for the project.
