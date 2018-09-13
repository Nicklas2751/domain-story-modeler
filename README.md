## Domain Storytelling Modeler
A tool to visualize Domain Stories in your browser.

### About 
http://domainstorytelling.org

### Run the Modeler
You can try the modeler online at https://www.wps.de/modeler.
To run the modeler locally, download the latest release from [GitHub](https://github.com/WPS/domain-story-modeler/releases).
Extract the zip file and open index.html in your browser.

### Usage
This is a short guide on how to use the Domain Story Modeler.

#### Pallet
Shows the icons you can choose to tell your Domain Story.

#### Headline
Click on the headline to change the name of the Domain Story and describe it.

#### Context Menu
If you drop an icon from the pallet into the canvas you will see a context menu. To show the connection between two icons use the arrow. Also you can choose the next icon you want to connect to. If you choose one, it will automatically be connected. Delete the choosen icon by clicking on delete. You can click on the wrench to change the icon. By using the annotation icon, you can add comments for further information.

#### Label 
Double click on an icon or an activity to add a label. 

#### Automatic Numbering
If you draw an activity between an actor (person, people and system) and a workobject (folder, call, email, conversation, information) it will be numbered automatically. By double clicking on the activity you can manually change the number. All other numbers are adjusted automatically.

#### File Management
If you want to share your Domain Story or save it for future editing, you can export it as a .dst file by cklicking the export button ![Export Button](/images/archive.png). 
To import a diagram use the upload button ![Upload Button](/images/unarchive.png).
You can also export your diagram as a .svg file by clicking on the image button ![SVG Button](/images/image.png).

#### Replay
The replay feature helps you to re-tell a Domain Story sentence by sentence. When you start a replay with the play button ![Play Button](/images/play.png), all activities except the first one disappear. Clicking the forward button ![Forward Button](/images/forward.png) shows the next activity and clicking the previous button ![Previous Button](/images/previous.png) shows the previous one. Editing is disabled in replay mode, but you can zoom (mouse wheel up and down) and scroll (ctrl + mouse wheel up and down). The stop the replay, click the stop button ![Stop Button](/images/stop.png). 

## For Developers
Download the source code or clone the repository.
Please note that we use the main branch for development. The main branch contains the lates features und big fixes, but they might be undocumented and tested less thoroughly than a release. To be on the safe side, stick with the latest release branch.

Fetch dependencies:

```
npm install
```

Build and open the modeler in your browser:

```
npm run dev
```

## License
The Domain Story Modeler is licensed under GPLv3.0.
The Modeler uses  [bpmn-js](https://github.com/bpmn-io/bpmn-js) which is licensed under the bpmn.io license.

### GPLv3.0

Copyright (c) 2018 WPS - Workplace Solutions GmbH

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.

### bpmn.io License

Copyright (c) 2014-2016 camunda Services GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

The source code responsible for displaying the bpmn.io logo (two green cogwheels in a box) that links back to http://bpmn.io as part of rendered diagrams MUST NOT be removed or changed. When this software is being used in a website or application, the logo must stay fully visible and not visually overlapped by other elements.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
