# Field: Pinnable

Place a pin on a custom map image.

- Version: 0.2
- Date: 4 March 2013
- Requirements: Symphony 2.3 or later
- Author: Rowan Lewis

## Installation

1. Upload the 'pinnable_field' folder in this archive to your Symphony 'extensions' folder.

2. Enable it by selecting the "Field: Pinnable", choose Enable from the with-selected menu, then click Apply.

3. You can now add the "Pinnable" field to your sections.

## Usage

1. Add a new field of type 'Pinnable' to your section, and specificy location of the image to use (can be a complete absolute URL, or relative to document root)

2. When editing an entry, you may select a position by clicking on the image. The percent of the left and top offset is stored.

3. Include the field element in your datasource. It will return something like:

    <entry id="260">
        <test position-x="40.571" position-y="66.000" image-url="http://placehold.it/940x640" />
    </entry>
