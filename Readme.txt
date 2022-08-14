To enable this package in Sublime Text goto "Preferences > Browse Packages" and copy the Openbor folder to the directory you are taken to.

When you have a file type open that you want to use openbor highlighting for goto "View > Syntax > Openbor" or if you always want this file type to be associated with Openbor select "View > Syntax > Open all with current extenstion as > Openbor".

To enable the colour scheme goto "Preferences > Select colour scheme > Openbor".

To disable tab for autocomplete goto "Preferences > Key Bindings" and copy this to the right window:

[
	{ "keys": ["tab"], "command": "insert", "args": {"characters": "\t"} },
//	{ "keys": ["tab"], "command": "auto_complete", "args": {"mini": true, "default": "\t"},
//		"context":
//		[
//			{ "key": "auto_complete_visible", "operand": false },
//			{ "key": "selection_empty", "operator": "equal", "operand": true, "match_all": true },
//			{ "key": "setting.tab_completion", "operator": "equal", "operand": true },
//			{ "key": "preceding_text", "operator": "regex_match", "operand": ".*\\w", "match_all": true },
//		]
//	},
//	{ "keys": ["tab"], "command": "expand_snippet", "context":
//		[{ "key": "has_snippet" }]
//	},
//	{ "keys": ["tab"], "command": "reindent", "context":
//		[
//			{ "key": "setting.auto_indent", "operator": "equal", "operand": true },
//			{ "key": "selection_empty", "operator": "equal", "operand": true, "match_all": true },
//			{ "key": "preceding_text", "operator": "regex_match", "operand": "^$", "match_all": true },
//			{ "key": "following_text", "operator": "regex_match", "operand": "^$", "match_all": true }
//		]
//	},
//	{ "keys": ["tab"], "command": "indent", "context":
//		[{ "key": "text", "operator": "regex_contains", "operand": "\n" }]
//	},
//	{ "keys": ["tab"], "command": "move", "args": {"by": "lines", "forward": true}, "context":
//		[
//		 	{ "key": "overlay_has_focus", "operator": "equal", "operand": true  }
//		]
//	},
//	{ "keys": ["tab"], "command": "next_field", "context":
//		[{ "key": "has_next_field", "operator": "equal", "operand": true }]
//	},
//	{ "keys": ["tab"], "command": "commit_completion", "context":
//		[{ "key": "auto_complete_visible" }]
//	},
]
