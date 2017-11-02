# Close

**Close** is an *extension* for the the [Adapt framework](https://github.com/adaptlearning/adapt_framework).   

An extension to add a close button and/or prompts.  

## Installation

This extension must be manually installed.  

If **Close** has been uninstalled from the Adapt authoring tool, it may be reinstalled using the [Plug-in Manager](https://github.com/adaptlearning/adapt_authoring/wiki/Plugin-Manager).  

## Usage

* A close button can be added to the navigation bar.
* Prompts using notify can be triggered on this button.
* In addition, browser dialogs can be displayed if you close the window in a normal fashion.

## Attributes

<table>
	<tr>
		<th colspan="3">Attribute<br></th>
		<th>Type</th>
		<th>Description</th>
		<th>Default</th>
	</tr>
	<tr>
		<td rowspan="11"><code>_button</code></td>
		<td colspan="2"><code>_isEnabled</code></td>
		<td>Boolean</td>
		<td>Adds a close button to the navigation bar</td>
		<td><code>false</code></td>
	</tr>
	<tr>
		<td rowspan="5"><code>_notifyPromptIfIncomplete</code></td>
		<td><code>_isEnabled</code></td>
		<td>Boolean</td>
		<td>Displays a notify prompt if the close button is selected while the course is incomplete</td>
		<td><code>false</code></td>
	</tr>
	<tr>
		<td><code>title</code></td>
		<td>String</td>
		<td>Prompt title</td>
		<td><code>"Confirm close"</code></td>
	</tr>
	<tr>
		<td><code>body</code></td>
		<td>String</td>
		<td>Prompt message<br></td>
		<td><code>"Are you sure you want to close the window?"</code></td>
	</tr>
	<tr>
		<td><code>confirm</code></td>
		<td>String</td>
		<td>Confirm button text</td>
		<td><code>"Close window"</code></td>
	</tr>
	<tr>
		<td><code>cancel</code></td>
		<td>String</td>
		<td>Cancel button text<br></td>
		<td><code>"Cancel"</code></td>
	</tr>
	<tr>
		<td rowspan="5"><code>_notifyPromptIfComplete</code></td>
		<td><code>_isEnabled</code></td>
		<td>Boolean</td>
		<td>Displays a notify prompt if the close button is selected after the course has been completed</td>
		<td><code>false</code></td>
	</tr>
	<tr>
		<td><code>title</code></td>
		<td>String</td>
		<td>Prompt title</td>
		<td><code>"Confirm close"</code></td>
	</tr>
	<tr>
		<td><code>body</code></td>
		<td>String</td>
		<td>Prompt message</td>
		<td><code>"Are you sure you want to close the window?"</code></td>
	</tr>
	<tr>
		<td><code>confirm</code></td>
		<td>String</td>
		<td>Confirm button text</td>
		<td><code>"Close window"</code></td>
	</tr>
	<tr>
		<td><code>cancel</code></td>
		<td>String</td>
		<td>Cancel button text</td>
		<td><code>"Cancel"</code></td>
	</tr>
	<tr>
		<td colspan="3"><code>browserPromptIfIncomplete</code></td>
		<td>String</td>
		<td>Populate with text to display a browser dialog if the window is closed while the course is incomplete</td>
		<td><code>""</code></td>
	</tr>
	<tr>
		<td colspan="3"><code>browserPromptIfComplete</code></td>
		<td>String<br></td>
		<td>Populate with text to display a browser dialog if the window is closed after the course has been completed</td>
		<td><code>""</code></td>
	</tr>
</table>

## Limitations

Firefox doesn’t currently support custom messages in its dialogs.

----------------------------
**Version number:**  2.1.1   
**Framework versions supported:**  2.0.6    
**Author / maintainer:** [C&G Kineo](https://github.com/cgkineo/adapt-close) / DeltaNet with [contributors](https://github.com/deltanet/adapt-close/graphs/contributors)     
**Accessibility support:** Yes  
**RTL support:** Yes     
**Authoring tool support:** Yes
