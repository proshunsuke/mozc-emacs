# Mozcをemacsのキーバインド風にする

### 使い方
1. Mozcを起動
2. Mozcツール > 設定ツール
3. キー設定 > キー設定の選択 > カスタム > 編集
4. 編集 > インポート
5. `keymap-emacs.txt`を選択

### キー設定
|モード|入力キー|コマンド|
|:-----------|:------------|:-------------|
|入力文字なし|Ctrl Shift Space|InsertFullSpace|
|入力文字なし|Shift Muhenkan|	ToggleAlphanumericMode|
|入力文字なし|	Shift Space|	InsertAlternateSpace|
|入力文字なし|	Space|	InsertSpace|
|入力文字なし|	Backspace|	Revert|
|変換前入力|	Backspace|	Backspace|
|変換前入力|	Ctrl a|	MoveCursorToBeginning|
|変換前入力|	Ctrl Backspace|	Backspace|
|変換前入力|	Ctrl d|	MoveCursorRight|
|変換前入力|	Ctrl e|	MoveCursorToEnd|
|変換前入力|	Ctrl a|	MoveCursorToBeginning|
|変換前入力|	Ctrl Enter|	Commit|
|変換前入力|	Ctrl g|	Delete|
|変換前入力|	Ctrl h|	Backspace|
|変換前入力|	Ctrl i|	ConvertToFullKatakana|
|変換前入力|	Ctrl b|	MoveCursorLeft|
|変換前入力|	Ctrl f|	MoveCursorRight|
|変換前入力|	Ctrl o|	ConvertToHalfWidth|
|変換前入力|	Ctrl Space|	InsertHalfSpace|
|変換前入力|	Ctrl Shift Space|	InsertFullSpace|
|変換前入力|	Ctrl t|	ConvertToHalfAlphanumeric|
|変換前入力|	Ctrl u|	ConvertToHiragana|
|変換前入力|	Ctrl z|	Cancel|
|変換前入力|	Delete|	Delete|
|変換前入力|	Enter|	Commit|
|変換前入力|	ESC|	Cancel|
|変換前入力|	Left|	MoveCursorLeft|
|変換前入力|	Right|	MoveCursorRight|
|変換前入力|	Shift Backspace|	Backspace|
|変換前入力|	Shift ESC|	Cancel|
|変換前入力|	Shift Left|	MoveCursorLeft|
|変換前入力|	Shift Right|	MoveCursorRight|
|変換前入力|	Space|	Convert|
|変換前入力|	Tab|	PredictAndConvert|
|サジェスト表示中|	Down|	PredictAndConvert|
|サジェスト表示中|	Shift Enter|	CommitFirstSuggestion|
|変換中|	Backspace|	Cancel|
|変換中|	Ctrl a|	SegmentFocusFirst|
|変換中|	Ctrl Backspace|	Cancel|
|変換中|	Ctrl Down|	CommitOnlyFirstSegment|
|変換中|	Ctrl Enter|	Commit|
|変換中|	Ctrl f|	SegmentFocusRight|
|変換中|	Ctrl g|	Cancel|
|変換中|	Ctrl h|	Cancel|
|変換中|	Ctrl i|	SegmentWidthShrink|
|変換中|	Ctrl k|	SegmentWidthShrink|
|変換中|	Ctrl l|	SegmentWidthExpand|
|変換中|	Ctrl Left|	SegmentFocusFirst|
|変換中|	Ctrl n|	ConvertNext|
|変換中|	Ctrl o|	SegmentWidthExpand|
|変換中|	Ctrl p|	ConvertPrev|
|変換中|	Ctrl Right|	SegmentFocusLast|
|変換中|	Ctrl b|	SegmentFocusLeft|
|変換中|	Ctrl Space|	InsertHalfSpace|
|変換中|	Ctrl Shift Space|	InsertFullSpace|
|変換中|	Ctrl t|	ConvertToHalfAlphanumeric|
|変換中|	Ctrl u|	ConvertToHiragana|
|変換中|	Ctrl Up|	ConvertPrev|
|変換中|	Ctrl z|	Cancel|
|変換中|	Delete|	Cancel|
|変換中|	Down|	ConvertNext|
|変換中|	End|	SegmentFocusLast|
|変換中|	Enter|	Commit|
|変換中|	ESC|	Cancel|
|変換中|	Home|	SegmentFocusFirst|
|変換中|	Left|	SegmentFocusLeft|
|変換中|	PageDown|	ConvertNextPage|
|変換中|	PageUp|	ConvertPrevPage|
|変換中|	Right|	SegmentFocusRight|
|変換中|	Shift Backspace|	Cancel|
|変換中|	Shift Down|	ConvertNextPage|
|変換中|	Shift ESC|	Cancel|
|変換中|	Shift Henkan|	ConvertPrev|
|変換中|	Shift Left|	SegmentWidthShrink|
|変換中|	Shift Muhenkan|	ConvertToFullAlphanumeric|
|変換中|	Shift Right|	SegmentWidthExpand|
|変換中|	Shift Space|	ConvertPrev|
|変換中|	Shift Up|	ConvertPrevPage|
|変換中|	Space|	PredictAndConvert|
|変換中|	Tab|	PredictAndConvert|
|変換中|	Up|	ConvertPrev|
|変換中|	Ctrl v|	ConvertNextPage|
|変換中|	Alt v|	ConvertPrevPage|

