# NOT WORKING DRAFT
# Keyword Cloud Block Plugin
A sidebar block plugin for [Open Monograph Press](https://github.com/pkp/omp) which displays a tag cloud of keywords.

The plugin found at: [https://github.com/ali-sokhandan/ojs3-keywordcloud-plugin](https://github.com/ali-sokhandan/ojs3-keywordcloud-plugin) 

Doesn't work with OMP3.1.1-1

It returns an error in this call:

`$journal = $request->getJournal();`

KeywordCloudBlockPlugin.inc.php on line 49

At this stage this DRAFT makes the right calls but the keywords cloud is empty.

![](snapshot.gif)

## About
This plugin creates an additional sidebar block. When added to a sidebar, it displays a tag cloud of keywords of articles.

## License
This plugin is licensed under the GNU General Public License v2. See the file
COPYING for the complete terms of this license.

## Install
 * Copy the release source or unpack the release package into the OJS i.e. OMP plugins/blocks/keywordCloud/ folder.
 * Go to Settings -> Website -> Plugins -> Block Plugins -> KeywordCloud Plugin and enable the plugin.
 * Go to Settings -> Website -> Appearance -> Sidebar management -> and drag the "Keyword Cloud Plugin" to the sidebar section.

## Compatibility
This plugin is compatible with OJS 3.1.x and OMP 1.2.x.
