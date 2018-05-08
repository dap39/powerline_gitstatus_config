# powerline_gitstatus_config
My powerline-gitstatus config

Clone on $HOME/.local/lib/python2.7/site-packages/powerline/config_files

Changes done:
$HOME/.local/lib/python2.7/site-packages/powerline/config_files/colorschemes/default.json:

{
	"groups": {
		"gitstatus":                 { "fg": "gray8",           "bg": "gray2", "attrs": [] },
		"gitstatus_branch":          { "fg": "gray8",           "bg": "gray2", "attrs": [] },
		"gitstatus_branch_clean":    { "fg": "green",           "bg": "gray2", "attrs": [] },
		"gitstatus_branch_dirty":    { "fg": "gray8",           "bg": "gray2", "attrs": [] },
		"gitstatus_branch_detached": { "fg": "mediumpurple",    "bg": "gray2", "attrs": [] },
		"gitstatus_tag":             { "fg": "darkcyan",        "bg": "gray2", "attrs": [] },
		"gitstatus_behind":          { "fg": "gray10",          "bg": "gray2", "attrs": [] },
		"gitstatus_ahead":           { "fg": "gray10",          "bg": "gray2", "attrs": [] },
		"gitstatus_staged":          { "fg": "green",           "bg": "gray2", "attrs": [] },
		"gitstatus_unmerged":        { "fg": "brightred",       "bg": "gray2", "attrs": [] },
		"gitstatus_changed":         { "fg": "mediumorange",    "bg": "gray2", "attrs": [] },
		"gitstatus_untracked":       { "fg": "brightestorange", "bg": "gray2", "attrs": [] },
		"gitstatus_stashed":         { "fg": "darkblue",        "bg": "gray2", "attrs": [] },
		"gitstatus:divider":         { "fg": "gray8",           "bg": "gray2", "attrs": [] }
	}
}


$HOME/.local/lib/python2.7/site-packages/powerline/config_files/themes/shell/default.json:

			{
				"function": "powerline_gitstatus.gitstatus",
				"priority": 40
			}
(be sure that this is done on the "left" segment).
