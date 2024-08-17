---
layout: page
title: MINIMIZE MISCLASSICATION COST 
description: Type 1 and Type 2 Errors Result In Different Loss To The Business
img: assets/img/7.jpg
importance: 4
category: fun
---

<!DOCTYPE html>

<html lang="en">
<head><meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>CaseStudy_MinimizeMisclassicationCost</title><script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: var(--jp-cell-editor-active-background) }
.highlight { background: var(--jp-cell-editor-background); color: var(--jp-mirror-editor-variable-color) }
.highlight .c { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment */
.highlight .err { color: var(--jp-mirror-editor-error-color) } /* Error */
.highlight .k { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword */
.highlight .o { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator */
.highlight .p { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation */
.highlight .ch { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Multiline */
.highlight .cp { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Preproc */
.highlight .cpf { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Single */
.highlight .cs { color: var(--jp-mirror-editor-comment-color); font-style: italic } /* Comment.Special */
.highlight .kc { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Pseudo */
.highlight .kr { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: var(--jp-mirror-editor-keyword-color); font-weight: bold } /* Keyword.Type */
.highlight .m { color: var(--jp-mirror-editor-number-color) } /* Literal.Number */
.highlight .s { color: var(--jp-mirror-editor-string-color) } /* Literal.String */
.highlight .ow { color: var(--jp-mirror-editor-operator-color); font-weight: bold } /* Operator.Word */
.highlight .pm { color: var(--jp-mirror-editor-punctuation-color) } /* Punctuation.Marker */
.highlight .w { color: var(--jp-mirror-editor-variable-color) } /* Text.Whitespace */
.highlight .mb { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Bin */
.highlight .mf { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Float */
.highlight .mh { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Hex */
.highlight .mi { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer */
.highlight .mo { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Oct */
.highlight .sa { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Affix */
.highlight .sb { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Backtick */
.highlight .sc { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Char */
.highlight .dl { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Delimiter */
.highlight .sd { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Doc */
.highlight .s2 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Double */
.highlight .se { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Escape */
.highlight .sh { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Heredoc */
.highlight .si { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Interpol */
.highlight .sx { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Other */
.highlight .sr { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Regex */
.highlight .s1 { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Single */
.highlight .ss { color: var(--jp-mirror-editor-string-color) } /* Literal.String.Symbol */
.highlight .il { color: var(--jp-mirror-editor-number-color) } /* Literal.Number.Integer.Long */
  </style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
 * Mozilla scrollbar styling
 */

/* use standard opaque scrollbars for most nodes */
[data-jp-theme-scrollbars='true'] {
  scrollbar-color: rgb(var(--jp-scrollbar-thumb-color))
    var(--jp-scrollbar-background-color);
}

/* for code nodes, use a transparent style of scrollbar. These selectors
 * will match lower in the tree, and so will override the above */
[data-jp-theme-scrollbars='true'] .CodeMirror-hscrollbar,
[data-jp-theme-scrollbars='true'] .CodeMirror-vscrollbar {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
}

/* tiny scrollbar */

.jp-scrollbar-tiny {
  scrollbar-color: rgba(var(--jp-scrollbar-thumb-color), 0.5) transparent;
  scrollbar-width: thin;
}

/* tiny scrollbar */

.jp-scrollbar-tiny::-webkit-scrollbar,
.jp-scrollbar-tiny::-webkit-scrollbar-corner {
  background-color: transparent;
  height: 4px;
  width: 4px;
}

.jp-scrollbar-tiny::-webkit-scrollbar-thumb {
  background: rgba(var(--jp-scrollbar-thumb-color), 0.5);
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:horizontal {
  border-left: 0 solid transparent;
  border-right: 0 solid transparent;
}

.jp-scrollbar-tiny::-webkit-scrollbar-track:vertical {
  border-top: 0 solid transparent;
  border-bottom: 0 solid transparent;
}

/*
 * Lumino
 */

.lm-ScrollBar[data-orientation='horizontal'] {
  min-height: 16px;
  max-height: 16px;
  min-width: 45px;
  border-top: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] {
  min-width: 16px;
  max-width: 16px;
  min-height: 45px;
  border-left: 1px solid #a0a0a0;
}

.lm-ScrollBar-button {
  background-color: #f0f0f0;
  background-position: center center;
  min-height: 15px;
  max-height: 15px;
  min-width: 15px;
  max-width: 15px;
}

.lm-ScrollBar-button:hover {
  background-color: #dadada;
}

.lm-ScrollBar-button.lm-mod-active {
  background-color: #cdcdcd;
}

.lm-ScrollBar-track {
  background: #f0f0f0;
}

.lm-ScrollBar-thumb {
  background: #cdcdcd;
}

.lm-ScrollBar-thumb:hover {
  background: #bababa;
}

.lm-ScrollBar-thumb.lm-mod-active {
  background: #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal'] .lm-ScrollBar-thumb {
  height: 100%;
  min-width: 15px;
  border-left: 1px solid #a0a0a0;
  border-right: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='vertical'] .lm-ScrollBar-thumb {
  width: 100%;
  min-height: 15px;
  border-top: 1px solid #a0a0a0;
  border-bottom: 1px solid #a0a0a0;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-left);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='horizontal']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-right);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='decrement'] {
  background-image: var(--jp-icon-caret-up);
  background-size: 17px;
}

.lm-ScrollBar[data-orientation='vertical']
  .lm-ScrollBar-button[data-action='increment'] {
  background-image: var(--jp-icon-caret-down);
  background-size: 17px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Widget {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
}

.lm-Widget.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.lm-AccordionPanel[data-orientation='horizontal'] > .lm-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  display: flex;
  flex-direction: column;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-CommandPalette-search {
  flex: 0 0 auto;
}

.lm-CommandPalette-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  min-height: 0;
  overflow: auto;
  list-style-type: none;
}

.lm-CommandPalette-header {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-CommandPalette-item {
  display: flex;
  flex-direction: row;
}

.lm-CommandPalette-itemIcon {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemContent {
  flex: 1 1 auto;
  overflow: hidden;
}

.lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemLabel {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.lm-close-icon {
  border: 1px solid transparent;
  background-color: transparent;
  position: absolute;
  z-index: 1;
  right: 3%;
  top: 0;
  bottom: 0;
  margin: auto;
  padding: 7px 0;
  display: none;
  vertical-align: middle;
  outline: 0;
  cursor: pointer;
}
.lm-close-icon:after {
  content: 'X';
  display: block;
  width: 15px;
  height: 15px;
  text-align: center;
  color: #000;
  font-weight: normal;
  font-size: 12px;
  cursor: pointer;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-DockPanel {
  z-index: 0;
}

.lm-DockPanel-widget {
  z-index: 0;
}

.lm-DockPanel-tabBar {
  z-index: 1;
}

.lm-DockPanel-handle {
  z-index: 2;
}

.lm-DockPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-DockPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-DockPanel-handle[data-orientation='horizontal'] {
  cursor: ew-resize;
}

.lm-DockPanel-handle[data-orientation='vertical'] {
  cursor: ns-resize;
}

.lm-DockPanel-handle[data-orientation='horizontal']:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-DockPanel-handle[data-orientation='vertical']:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

.lm-DockPanel-overlay {
  z-index: 3;
  box-sizing: border-box;
  pointer-events: none;
}

.lm-DockPanel-overlay.lm-mod-hidden {
  display: none !important;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-Menu {
  z-index: 10000;
  position: absolute;
  white-space: nowrap;
  overflow-x: hidden;
  overflow-y: auto;
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-Menu-content {
  margin: 0;
  padding: 0;
  display: table;
  list-style-type: none;
}

.lm-Menu-item {
  display: table-row;
}

.lm-Menu-item.lm-mod-hidden,
.lm-Menu-item.lm-mod-collapsed {
  display: none !important;
}

.lm-Menu-itemIcon,
.lm-Menu-itemSubmenuIcon {
  display: table-cell;
  text-align: center;
}

.lm-Menu-itemLabel {
  display: table-cell;
  text-align: left;
}

.lm-Menu-itemShortcut {
  display: table-cell;
  text-align: right;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-MenuBar {
  outline: none;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-MenuBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex-direction: row;
  list-style-type: none;
}

.lm-MenuBar-item {
  box-sizing: border-box;
}

.lm-MenuBar-itemIcon,
.lm-MenuBar-itemLabel {
  display: inline-block;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-ScrollBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-ScrollBar[data-orientation='horizontal'] {
  flex-direction: row;
}

.lm-ScrollBar[data-orientation='vertical'] {
  flex-direction: column;
}

.lm-ScrollBar-button {
  box-sizing: border-box;
  flex: 0 0 auto;
}

.lm-ScrollBar-track {
  box-sizing: border-box;
  position: relative;
  overflow: hidden;
  flex: 1 1 auto;
}

.lm-ScrollBar-thumb {
  box-sizing: border-box;
  position: absolute;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-SplitPanel-child {
  z-index: 0;
}

.lm-SplitPanel-handle {
  z-index: 1;
}

.lm-SplitPanel-handle.lm-mod-hidden {
  display: none !important;
}

.lm-SplitPanel-handle:after {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  content: '';
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle {
  cursor: ew-resize;
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle {
  cursor: ns-resize;
}

.lm-SplitPanel[data-orientation='horizontal'] > .lm-SplitPanel-handle:after {
  left: 50%;
  min-width: 8px;
  transform: translateX(-50%);
}

.lm-SplitPanel[data-orientation='vertical'] > .lm-SplitPanel-handle:after {
  top: 50%;
  min-height: 8px;
  transform: translateY(-50%);
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabBar {
  display: flex;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.lm-TabBar[data-orientation='horizontal'] {
  flex-direction: row;
  align-items: flex-end;
}

.lm-TabBar[data-orientation='vertical'] {
  flex-direction: column;
  align-items: flex-end;
}

.lm-TabBar-content {
  margin: 0;
  padding: 0;
  display: flex;
  flex: 1 1 auto;
  list-style-type: none;
}

.lm-TabBar[data-orientation='horizontal'] > .lm-TabBar-content {
  flex-direction: row;
}

.lm-TabBar[data-orientation='vertical'] > .lm-TabBar-content {
  flex-direction: column;
}

.lm-TabBar-tab {
  display: flex;
  flex-direction: row;
  box-sizing: border-box;
  overflow: hidden;
  touch-action: none; /* Disable native Drag/Drop */
}

.lm-TabBar-tabIcon,
.lm-TabBar-tabCloseIcon {
  flex: 0 0 auto;
}

.lm-TabBar-tabLabel {
  flex: 1 1 auto;
  overflow: hidden;
  white-space: nowrap;
}

.lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
}

.lm-TabBar-tab.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar-addButton.lm-mod-hidden {
  display: none !important;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab {
  position: relative;
}

.lm-TabBar.lm-mod-dragging[data-orientation='horizontal'] .lm-TabBar-tab {
  left: 0;
  transition: left 150ms ease;
}

.lm-TabBar.lm-mod-dragging[data-orientation='vertical'] .lm-TabBar-tab {
  top: 0;
  transition: top 150ms ease;
}

.lm-TabBar.lm-mod-dragging .lm-TabBar-tab.lm-mod-dragging {
  transition: none;
}

.lm-TabBar-tabLabel .lm-TabBar-tabInput {
  user-select: all;
  width: 100%;
  box-sizing: border-box;
  background: inherit;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-TabPanel-tabBar {
  z-index: 1;
}

.lm-TabPanel-stackedPanel {
  z-index: 0;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapse {
  display: flex;
  flex-direction: column;
  align-items: stretch;
}

.jp-Collapse-header {
  padding: 1px 12px;
  background-color: var(--jp-layout-color1);
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  align-items: center;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  text-transform: uppercase;
  user-select: none;
}

.jp-Collapser-icon {
  height: 16px;
}

.jp-Collapse-header-collapsed .jp-Collapser-icon {
  transform: rotate(-90deg);
  margin: auto 0;
}

.jp-Collapser-title {
  line-height: 25px;
}

.jp-Collapse-contents {
  padding: 0 12px;
  background-color: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* This file was auto-generated by ensureUiComponents() in @jupyterlab/buildutils */

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

/* Icons urls */

:root {
  --jp-icon-add-above: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5MikiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik00Ljc1IDQuOTMwNjZINi42MjVWNi44MDU2NkM2LjYyNSA3LjAxMTkxIDYuNzkzNzUgNy4xODA2NiA3IDcuMTgwNjZDNy4yMDYyNSA3LjE4MDY2IDcuMzc1IDcuMDExOTEgNy4zNzUgNi44MDU2NlY0LjkzMDY2SDkuMjVDOS40NTYyNSA0LjkzMDY2IDkuNjI1IDQuNzYxOTEgOS42MjUgNC41NTU2NkM5LjYyNSA0LjM0OTQxIDkuNDU2MjUgNC4xODA2NiA5LjI1IDQuMTgwNjZINy4zNzVWMi4zMDU2NkM3LjM3NSAyLjA5OTQxIDcuMjA2MjUgMS45MzA2NiA3IDEuOTMwNjZDNi43OTM3NSAxLjkzMDY2IDYuNjI1IDIuMDk5NDEgNi42MjUgMi4zMDU2NlY0LjE4MDY2SDQuNzVDNC41NDM3NSA0LjE4MDY2IDQuMzc1IDQuMzQ5NDEgNC4zNzUgNC41NTU2NkM0LjM3NSA0Ljc2MTkxIDQuNTQzNzUgNC45MzA2NiA0Ljc1IDQuOTMwNjZaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC43Ii8+CjwvZz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTExLjUgOS41VjExLjVMMi41IDExLjVWOS41TDExLjUgOS41Wk0xMiA4QzEyLjU1MjMgOCAxMyA4LjQ0NzcyIDEzIDlWMTJDMTMgMTIuNTUyMyAxMi41NTIzIDEzIDEyIDEzTDIgMTNDMS40NDc3MiAxMyAxIDEyLjU1MjMgMSAxMlY5QzEgOC40NDc3MiAxLjQ0NzcxIDggMiA4TDEyIDhaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5MiI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KC0xIDAgMCAxIDEwIDEuNTU1NjYpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==);
  --jp-icon-add-below: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwXzEzN18xOTQ5OCkiPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGQ9Ik05LjI1IDEwLjA2OTNMNy4zNzUgMTAuMDY5M0w3LjM3NSA4LjE5NDM0QzcuMzc1IDcuOTg4MDkgNy4yMDYyNSA3LjgxOTM0IDcgNy44MTkzNEM2Ljc5Mzc1IDcuODE5MzQgNi42MjUgNy45ODgwOSA2LjYyNSA4LjE5NDM0TDYuNjI1IDEwLjA2OTNMNC43NSAxMC4wNjkzQzQuNTQzNzUgMTAuMDY5MyA0LjM3NSAxMC4yMzgxIDQuMzc1IDEwLjQ0NDNDNC4zNzUgMTAuNjUwNiA0LjU0Mzc1IDEwLjgxOTMgNC43NSAxMC44MTkzTDYuNjI1IDEwLjgxOTNMNi42MjUgMTIuNjk0M0M2LjYyNSAxMi45MDA2IDYuNzkzNzUgMTMuMDY5MyA3IDEzLjA2OTNDNy4yMDYyNSAxMy4wNjkzIDcuMzc1IDEyLjkwMDYgNy4zNzUgMTIuNjk0M0w3LjM3NSAxMC44MTkzTDkuMjUgMTAuODE5M0M5LjQ1NjI1IDEwLjgxOTMgOS42MjUgMTAuNjUwNiA5LjYyNSAxMC40NDQzQzkuNjI1IDEwLjIzODEgOS40NTYyNSAxMC4wNjkzIDkuMjUgMTAuMDY5M1oiIGZpbGw9IiM2MTYxNjEiIHN0cm9rZT0iIzYxNjE2MSIgc3Ryb2tlLXdpZHRoPSIwLjciLz4KPC9nPgo8cGF0aCBjbGFzcz0ianAtaWNvbjMiIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMi41IDUuNUwyLjUgMy41TDExLjUgMy41TDExLjUgNS41TDIuNSA1LjVaTTIgN0MxLjQ0NzcyIDcgMSA2LjU1MjI4IDEgNkwxIDNDMSAyLjQ0NzcyIDEuNDQ3NzIgMiAyIDJMMTIgMkMxMi41NTIzIDIgMTMgMi40NDc3MiAxMyAzTDEzIDZDMTMgNi41NTIyOSAxMi41NTIzIDcgMTIgN0wyIDdaIiBmaWxsPSIjNjE2MTYxIi8+CjxkZWZzPgo8Y2xpcFBhdGggaWQ9ImNsaXAwXzEzN18xOTQ5OCI+CjxyZWN0IGNsYXNzPSJqcC1pY29uMyIgd2lkdGg9IjYiIGhlaWdodD0iNiIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0ibWF0cml4KDEgMS43NDg0NmUtMDcgMS43NDg0NmUtMDcgLTEgNCAxMy40NDQzKSIvPgo8L2NsaXBQYXRoPgo8L2RlZnM+Cjwvc3ZnPgo=);
  --jp-icon-add: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDEzaC02djZoLTJ2LTZINXYtMmg2VjVoMnY2aDZ2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bell: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE2IDE2IiB2ZXJzaW9uPSIxLjEiPgogICA8cGF0aCBjbGFzcz0ianAtaWNvbjIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzMzMzMzIgogICAgICBkPSJtOCAwLjI5Yy0xLjQgMC0yLjcgMC43My0zLjYgMS44LTEuMiAxLjUtMS40IDMuNC0xLjUgNS4yLTAuMTggMi4yLTAuNDQgNC0yLjMgNS4zbDAuMjggMS4zaDVjMC4wMjYgMC42NiAwLjMyIDEuMSAwLjcxIDEuNSAwLjg0IDAuNjEgMiAwLjYxIDIuOCAwIDAuNTItMC40IDAuNi0xIDAuNzEtMS41aDVsMC4yOC0xLjNjLTEuOS0wLjk3LTIuMi0zLjMtMi4zLTUuMy0wLjEzLTEuOC0wLjI2LTMuNy0xLjUtNS4yLTAuODUtMS0yLjItMS44LTMuNi0xLjh6bTAgMS40YzAuODggMCAxLjkgMC41NSAyLjUgMS4zIDAuODggMS4xIDEuMSAyLjcgMS4yIDQuNCAwLjEzIDEuNyAwLjIzIDMuNiAxLjMgNS4yaC0xMGMxLjEtMS42IDEuMi0zLjQgMS4zLTUuMiAwLjEzLTEuNyAwLjMtMy4zIDEuMi00LjQgMC41OS0wLjcyIDEuNi0xLjMgMi41LTEuM3ptLTAuNzQgMTJoMS41Yy0wLjAwMTUgMC4yOCAwLjAxNSAwLjc5LTAuNzQgMC43OS0wLjczIDAuMDAxNi0wLjcyLTAuNTMtMC43NC0wLjc5eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-bug-dot: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiPgogICAgICAgIDxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNMTcuMTkgOEgyMFYxMEgxNy45MUMxNy45NiAxMC4zMyAxOCAxMC42NiAxOCAxMVYxMkgyMFYxNEgxOC41SDE4VjE0LjAyNzVDMTUuNzUgMTQuMjc2MiAxNCAxNi4xODM3IDE0IDE4LjVDMTQgMTkuMjA4IDE0LjE2MzUgMTkuODc3OSAxNC40NTQ5IDIwLjQ3MzlDMTMuNzA2MyAyMC44MTE3IDEyLjg3NTcgMjEgMTIgMjFDOS43OCAyMSA3Ljg1IDE5Ljc5IDYuODEgMThINFYxNkg2LjA5QzYuMDQgMTUuNjcgNiAxNS4zNCA2IDE1VjE0SDRWMTJINlYxMUM2IDEwLjY2IDYuMDQgMTAuMzMgNi4wOSAxMEg0VjhINi44MUM3LjI2IDcuMjIgNy44OCA2LjU1IDguNjIgNi4wNEw3IDQuNDFMOC40MSAzTDEwLjU5IDUuMTdDMTEuMDQgNS4wNiAxMS41MSA1IDEyIDVDMTIuNDkgNSAxMi45NiA1LjA2IDEzLjQyIDUuMTdMMTUuNTkgM0wxNyA0LjQxTDE1LjM3IDYuMDRDMTYuMTIgNi41NSAxNi43NCA3LjIyIDE3LjE5IDhaTTEwIDE2SDE0VjE0SDEwVjE2Wk0xMCAxMkgxNFYxMEgxMFYxMloiIGZpbGw9IiM2MTYxNjEiLz4KICAgICAgICA8cGF0aCBkPSJNMjIgMTguNUMyMiAyMC40MzMgMjAuNDMzIDIyIDE4LjUgMjJDMTYuNTY3IDIyIDE1IDIwLjQzMyAxNSAxOC41QzE1IDE2LjU2NyAxNi41NjcgMTUgMTguNSAxNUMyMC40MzMgMTUgMjIgMTYuNTY3IDIyIDE4LjVaIiBmaWxsPSIjNjE2MTYxIi8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-bug: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yMCA4aC0yLjgxYy0uNDUtLjc4LTEuMDctMS40NS0xLjgyLTEuOTZMMTcgNC40MSAxNS41OSAzbC0yLjE3IDIuMTdDMTIuOTYgNS4wNiAxMi40OSA1IDEyIDVjLS40OSAwLS45Ni4wNi0xLjQxLjE3TDguNDEgMyA3IDQuNDFsMS42MiAxLjYzQzcuODggNi41NSA3LjI2IDcuMjIgNi44MSA4SDR2MmgyLjA5Yy0uMDUuMzMtLjA5LjY2LS4wOSAxdjFINHYyaDJ2MWMwIC4zNC4wNC42Ny4wOSAxSDR2MmgyLjgxYzEuMDQgMS43OSAyLjk3IDMgNS4xOSAzczQuMTUtMS4yMSA1LjE5LTNIMjB2LTJoLTIuMDljLjA1LS4zMy4wOS0uNjYuMDktMXYtMWgydi0yaC0ydi0xYzAtLjM0LS4wNC0uNjctLjA5LTFIMjBWOHptLTYgOGgtNHYtMmg0djJ6bTAtNGgtNHYtMmg0djJ6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-build: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE0LjkgMTcuNDVDMTYuMjUgMTcuNDUgMTcuMzUgMTYuMzUgMTcuMzUgMTVDMTcuMzUgMTMuNjUgMTYuMjUgMTIuNTUgMTQuOSAxMi41NUMxMy41NCAxMi41NSAxMi40NSAxMy42NSAxMi40NSAxNUMxMi40NSAxNi4zNSAxMy41NCAxNy40NSAxNC45IDE3LjQ1Wk0yMC4xIDE1LjY4TDIxLjU4IDE2Ljg0QzIxLjcxIDE2Ljk1IDIxLjc1IDE3LjEzIDIxLjY2IDE3LjI5TDIwLjI2IDE5LjcxQzIwLjE3IDE5Ljg2IDIwIDE5LjkyIDE5LjgzIDE5Ljg2TDE4LjA5IDE5LjE2QzE3LjczIDE5LjQ0IDE3LjMzIDE5LjY3IDE2LjkxIDE5Ljg1TDE2LjY0IDIxLjdDMTYuNjIgMjEuODcgMTYuNDcgMjIgMTYuMyAyMkgxMy41QzEzLjMyIDIyIDEzLjE4IDIxLjg3IDEzLjE1IDIxLjdMMTIuODkgMTkuODVDMTIuNDYgMTkuNjcgMTIuMDcgMTkuNDQgMTEuNzEgMTkuMTZMOS45NjAwMiAxOS44NkM5LjgxMDAyIDE5LjkyIDkuNjIwMDIgMTkuODYgOS41NDAwMiAxOS43MUw4LjE0MDAyIDE3LjI5QzguMDUwMDIgMTcuMTMgOC4wOTAwMiAxNi45NSA4LjIyMDAyIDE2Ljg0TDkuNzAwMDIgMTUuNjhMOS42NTAwMSAxNUw5LjcwMDAyIDE0LjMxTDguMjIwMDIgMTMuMTZDOC4wOTAwMiAxMy4wNSA4LjA1MDAyIDEyLjg2IDguMTQwMDIgMTIuNzFMOS41NDAwMiAxMC4yOUM5LjYyMDAyIDEwLjEzIDkuODEwMDIgMTAuMDcgOS45NjAwMiAxMC4xM0wxMS43MSAxMC44NEMxMi4wNyAxMC41NiAxMi40NiAxMC4zMiAxMi44OSAxMC4xNUwxMy4xNSA4LjI4OTk4QzEzLjE4IDguMTI5OTggMTMuMzIgNy45OTk5OCAxMy41IDcuOTk5OThIMTYuM0MxNi40NyA3Ljk5OTk4IDE2LjYyIDguMTI5OTggMTYuNjQgOC4yODk5OEwxNi45MSAxMC4xNUMxNy4zMyAxMC4zMiAxNy43MyAxMC41NiAxOC4wOSAxMC44NEwxOS44MyAxMC4xM0MyMCAxMC4wNyAyMC4xNyAxMC4xMyAyMC4yNiAxMC4yOUwyMS42NiAxMi43MUMyMS43NSAxMi44NiAyMS43MSAxMy4wNSAyMS41OCAxMy4xNkwyMC4xIDE0LjMxTDIwLjE1IDE1TDIwLjEgMTUuNjhaIi8+CiAgICA8cGF0aCBkPSJNNy4zMjk2NiA3LjQ0NDU0QzguMDgzMSA3LjAwOTU0IDguMzM5MzIgNi4wNTMzMiA3LjkwNDMyIDUuMjk5ODhDNy40NjkzMiA0LjU0NjQzIDYuNTA4MSA0LjI4MTU2IDUuNzU0NjYgNC43MTY1NkM1LjM5MTc2IDQuOTI2MDggNS4xMjY5NSA1LjI3MTE4IDUuMDE4NDkgNS42NzU5NEM0LjkxMDA0IDYuMDgwNzEgNC45NjY4MiA2LjUxMTk4IDUuMTc2MzQgNi44NzQ4OEM1LjYxMTM0IDcuNjI4MzIgNi41NzYyMiA3Ljg3OTU0IDcuMzI5NjYgNy40NDQ1NFpNOS42NTcxOCA0Ljc5NTkzTDEwLjg2NzIgNC45NTE3OUMxMC45NjI4IDQuOTc3NDEgMTEuMDQwMiA1LjA3MTMzIDExLjAzODIgNS4xODc5M0wxMS4wMzg4IDYuOTg4OTNDMTEuMDQ1NSA3LjEwMDU0IDEwLjk2MTYgNy4xOTUxOCAxMC44NTUgNy4yMTA1NEw5LjY2MDAxIDcuMzgwODNMOS4yMzkxNSA4LjEzMTg4TDkuNjY5NjEgOS4yNTc0NUM5LjcwNzI5IDkuMzYyNzEgOS42NjkzNCA5LjQ3Njk5IDkuNTc0MDggOS41MzE5OUw4LjAxNTIzIDEwLjQzMkM3LjkxMTMxIDEwLjQ5MiA3Ljc5MzM3IDEwLjQ2NzcgNy43MjEwNSAxMC4zODI0TDYuOTg3NDggOS40MzE4OEw2LjEwOTMxIDkuNDMwODNMNS4zNDcwNCAxMC4zOTA1QzUuMjg5MDkgMTAuNDcwMiA1LjE3MzgzIDEwLjQ5MDUgNS4wNzE4NyAxMC40MzM5TDMuNTEyNDUgOS41MzI5M0MzLjQxMDQ5IDkuNDc2MzMgMy4zNzY0NyA5LjM1NzQxIDMuNDEwNzUgOS4yNTY3OUwzLjg2MzQ3IDguMTQwOTNMMy42MTc0OSA3Ljc3NDg4TDMuNDIzNDcgNy4zNzg4M0wyLjIzMDc1IDcuMjEyOTdDMi4xMjY0NyA3LjE5MjM1IDIuMDQwNDkgNy4xMDM0MiAyLjA0MjQ1IDYuOTg2ODJMMi4wNDE4NyA1LjE4NTgyQzIuMDQzODMgNS4wNjkyMiAyLjExOTA5IDQuOTc5NTggMi4yMTcwNCA0Ljk2OTIyTDMuNDIwNjUgNC43OTM5M0wzLjg2NzQ5IDQuMDI3ODhMMy40MTEwNSAyLjkxNzMxQzMuMzczMzcgMi44MTIwNCAzLjQxMTMxIDIuNjk3NzYgMy41MTUyMyAyLjYzNzc2TDUuMDc0MDggMS43Mzc3NkM1LjE2OTM0IDEuNjgyNzYgNS4yODcyOSAxLjcwNzA0IDUuMzU5NjEgMS43OTIzMUw2LjExOTE1IDIuNzI3ODhMNi45ODAwMSAyLjczODkzTDcuNzI0OTYgMS43ODkyMkM3Ljc5MTU2IDEuNzA0NTggNy45MTU0OCAxLjY3OTIyIDguMDA4NzkgMS43NDA4Mkw5LjU2ODIxIDIuNjQxODJDOS42NzAxNyAyLjY5ODQyIDkuNzEyODUgMi44MTIzNCA5LjY4NzIzIDIuOTA3OTdMOS4yMTcxOCA0LjAzMzgzTDkuNDYzMTYgNC4zOTk4OEw5LjY1NzE4IDQuNzk1OTNaIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iOS45LDEzLjYgMy42LDcuNCA0LjQsNi42IDkuOSwxMi4yIDE1LjQsNi43IDE2LjEsNy40ICIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNS45TDksOS43bDMuOC0zLjhsMS4yLDEuMmwtNC45LDVsLTQuOS01TDUuMiw1Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-caret-down: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik01LjIsNy41TDksMTEuMmwzLjgtMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-left: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik0xMC44LDEyLjhMNy4xLDlsMy44LTMuOGwwLDcuNkgxMC44eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-right: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiIHNoYXBlLXJlbmRlcmluZz0iZ2VvbWV0cmljUHJlY2lzaW9uIj4KICAgIDxwYXRoIGQ9Ik03LjIsNS4yTDEwLjksOWwtMy44LDMuOFY1LjJINy4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-caret-up-empty-thin: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwb2x5Z29uIGNsYXNzPSJzdDEiIHBvaW50cz0iMTUuNCwxMy4zIDkuOSw3LjcgNC40LDEzLjIgMy42LDEyLjUgOS45LDYuMyAxNi4xLDEyLjYgIi8+Cgk8L2c+Cjwvc3ZnPgo=);
  --jp-icon-caret-up: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSIgc2hhcGUtcmVuZGVyaW5nPSJnZW9tZXRyaWNQcmVjaXNpb24iPgoJCTxwYXRoIGQ9Ik01LjIsMTAuNUw5LDYuOGwzLjgsMy44SDUuMnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-case-sensitive: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWFjY2VudDIiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTcuNiw4aDAuOWwzLjUsOGgtMS4xTDEwLDE0SDZsLTAuOSwySDRMNy42LDh6IE04LDkuMUw2LjQsMTNoMy4yTDgsOS4xeiIvPgogICAgPHBhdGggZD0iTTE2LjYsOS44Yy0wLjIsMC4xLTAuNCwwLjEtMC43LDAuMWMtMC4yLDAtMC40LTAuMS0wLjYtMC4yYy0wLjEtMC4xLTAuMi0wLjQtMC4yLTAuNyBjLTAuMywwLjMtMC42LDAuNS0wLjksMC43Yy0wLjMsMC4xLTAuNywwLjItMS4xLDAuMmMtMC4zLDAtMC41LDAtMC43LTAuMWMtMC4yLTAuMS0wLjQtMC4yLTAuNi0wLjNjLTAuMi0wLjEtMC4zLTAuMy0wLjQtMC41IGMtMC4xLTAuMi0wLjEtMC40LTAuMS0wLjdjMC0wLjMsMC4xLTAuNiwwLjItMC44YzAuMS0wLjIsMC4zLTAuNCwwLjQtMC41QzEyLDcsMTIuMiw2LjksMTIuNSw2LjhjMC4yLTAuMSwwLjUtMC4xLDAuNy0wLjIgYzAuMy0wLjEsMC41LTAuMSwwLjctMC4xYzAuMiwwLDAuNC0wLjEsMC42LTAuMWMwLjIsMCwwLjMtMC4xLDAuNC0wLjJjMC4xLTAuMSwwLjItMC4yLDAuMi0wLjRjMC0xLTEuMS0xLTEuMy0xIGMtMC40LDAtMS40LDAtMS40LDEuMmgtMC45YzAtMC40LDAuMS0wLjcsMC4yLTFjMC4xLTAuMiwwLjMtMC40LDAuNS0wLjZjMC4yLTAuMiwwLjUtMC4zLDAuOC0wLjNDMTMuMyw0LDEzLjYsNCwxMy45LDQgYzAuMywwLDAuNSwwLDAuOCwwLjFjMC4zLDAsMC41LDAuMSwwLjcsMC4yYzAuMiwwLjEsMC40LDAuMywwLjUsMC41QzE2LDUsMTYsNS4yLDE2LDUuNnYyLjljMCwwLjIsMCwwLjQsMCwwLjUgYzAsMC4xLDAuMSwwLjIsMC4zLDAuMmMwLjEsMCwwLjIsMCwwLjMsMFY5Ljh6IE0xNS4yLDYuOWMtMS4yLDAuNi0zLjEsMC4yLTMuMSwxLjRjMCwxLjQsMy4xLDEsMy4xLTAuNVY2Ljl6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-circle-empty: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDJDNi40NyAyIDIgNi40NyAyIDEyczQuNDcgMTAgMTAgMTAgMTAtNC40NyAxMC0xMFMxNy41MyAyIDEyIDJ6bTAgMThjLTQuNDEgMC04LTMuNTktOC04czMuNTktOCA4LTggOCAzLjU5IDggOC0zLjU5IDgtOCA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-circle: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iOSIgY3k9IjkiIHI9IjgiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-clear: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8bWFzayBpZD0iZG9udXRIb2xlIj4KICAgIDxyZWN0IHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgZmlsbD0id2hpdGUiIC8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI4IiBmaWxsPSJibGFjayIvPgogIDwvbWFzaz4KCiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxyZWN0IGhlaWdodD0iMTgiIHdpZHRoPSIyIiB4PSIxMSIgeT0iMyIgdHJhbnNmb3JtPSJyb3RhdGUoMzE1LCAxMiwgMTIpIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIgbWFzaz0idXJsKCNkb251dEhvbGUpIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-close: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1ub25lIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIGpwLWljb24zLWhvdmVyIiBmaWxsPSJub25lIj4KICAgIDxjaXJjbGUgY3g9IjEyIiBjeT0iMTIiIHI9IjExIi8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIGpwLWljb24tYWNjZW50Mi1ob3ZlciIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMTkgNi40MUwxNy41OSA1IDEyIDEwLjU5IDYuNDEgNSA1IDYuNDEgMTAuNTkgMTIgNSAxNy41OSA2LjQxIDE5IDEyIDEzLjQxIDE3LjU5IDE5IDE5IDE3LjU5IDEzLjQxIDEyeiIvPgogIDwvZz4KCiAgPGcgY2xhc3M9ImpwLWljb24tbm9uZSBqcC1pY29uLWJ1c3kiIGZpbGw9Im5vbmUiPgogICAgPGNpcmNsZSBjeD0iMTIiIGN5PSIxMiIgcj0iNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code-check: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+CiAgICA8cGF0aCBkPSJNNi41OSwzLjQxTDIsOEw2LjU5LDEyLjZMOCwxMS4xOEw0LjgyLDhMOCw0LjgyTDYuNTksMy40MU0xMi40MSwzLjQxTDExLDQuODJMMTQuMTgsOEwxMSwxMS4xOEwxMi40MSwxMi42TDE3LDhMMTIuNDEsMy40MU0yMS41OSwxMS41OUwxMy41LDE5LjY4TDkuODMsMTZMOC40MiwxNy40MUwxMy41LDIyLjVMMjMsMTNMMjEuNTksMTEuNTlaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-code: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTExLjQgMTguNkw2LjggMTRMMTEuNCA5LjRMMTAgOEw0IDE0TDEwIDIwTDExLjQgMTguNlpNMTYuNiAxOC42TDIxLjIgMTRMMTYuNiA5LjRMMTggOEwyNCAxNEwxOCAyMEwxNi42IDE4LjZWMTguNloiLz4KCTwvZz4KPC9zdmc+Cg==);
  --jp-icon-collapse-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNNiAxM3YyaDh2LTJ6IiAvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-console: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwMCAyMDAiPgogIDxnIGNsYXNzPSJqcC1jb25zb2xlLWljb24tYmFja2dyb3VuZC1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMjg4RDEiPgogICAgPHBhdGggZD0iTTIwIDE5LjhoMTYwdjE1OS45SDIweiIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtY29uc29sZS1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIj4KICAgIDxwYXRoIGQ9Ik0xMDUgMTI3LjNoNDB2MTIuOGgtNDB6TTUxLjEgNzdMNzQgOTkuOWwtMjMuMyAyMy4zIDEwLjUgMTAuNSAyMy4zLTIzLjNMOTUgOTkuOSA4NC41IDg5LjQgNjEuNiA2Ni41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copy: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTExLjksMUgzLjJDMi40LDEsMS43LDEuNywxLjcsMi41djEwLjJoMS41VjIuNWg4LjdWMXogTTE0LjEsMy45aC04Yy0wLjgsMC0xLjUsMC43LTEuNSwxLjV2MTAuMmMwLDAuOCwwLjcsMS41LDEuNSwxLjVoOCBjMC44LDAsMS41LTAuNywxLjUtMS41VjUuNEMxNS41LDQuNiwxNC45LDMuOSwxNC4xLDMuOXogTTE0LjEsMTUuNWgtOFY1LjRoOFYxNS41eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-copyright: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCI+CiAgPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0xMS44OCw5LjE0YzEuMjgsMC4wNiwxLjYxLDEuMTUsMS42MywxLjY2aDEuNzljLTAuMDgtMS45OC0xLjQ5LTMuMTktMy40NS0zLjE5QzkuNjQsNy42MSw4LDksOCwxMi4xNCBjMCwxLjk0LDAuOTMsNC4yNCwzLjg0LDQuMjRjMi4yMiwwLDMuNDEtMS42NSwzLjQ0LTIuOTVoLTEuNzljLTAuMDMsMC41OS0wLjQ1LDEuMzgtMS42MywxLjQ0QzEwLjU1LDE0LjgzLDEwLDEzLjgxLDEwLDEyLjE0IEMxMCw5LjI1LDExLjI4LDkuMTYsMTEuODgsOS4xNHogTTEyLDJDNi40OCwyLDIsNi40OCwyLDEyczQuNDgsMTAsMTAsMTBzMTAtNC40OCwxMC0xMFMxNy41MiwyLDEyLDJ6IE0xMiwyMGMtNC40MSwwLTgtMy41OS04LTggczMuNTktOCw4LThzOCwzLjU5LDgsOFMxNi40MSwyMCwxMiwyMHoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-cut: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkuNjQgNy42NGMuMjMtLjUuMzYtMS4wNS4zNi0xLjY0IDAtMi4yMS0xLjc5LTQtNC00UzIgMy43OSAyIDZzMS43OSA0IDQgNGMuNTkgMCAxLjE0LS4xMyAxLjY0LS4zNkwxMCAxMmwtMi4zNiAyLjM2QzcuMTQgMTQuMTMgNi41OSAxNCA2IDE0Yy0yLjIxIDAtNCAxLjc5LTQgNHMxLjc5IDQgNCA0IDQtMS43OSA0LTRjMC0uNTktLjEzLTEuMTQtLjM2LTEuNjRMMTIgMTRsNyA3aDN2LTFMOS42NCA3LjY0ek02IDhjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTAgMTJjLTEuMSAwLTItLjg5LTItMnMuOS0yIDItMiAyIC44OSAyIDItLjkgMi0yIDJ6bTYtNy41Yy0uMjggMC0uNS0uMjItLjUtLjVzLjIyLS41LjUtLjUuNS4yMi41LjUtLjIyLjUtLjUuNXpNMTkgM2wtNiA2IDIgMiA3LTdWM3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-delete: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2cHgiIGhlaWdodD0iMTZweCI+CiAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIiAvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjI2MjYyIiBkPSJNNiAxOWMwIDEuMS45IDIgMiAyaDhjMS4xIDAgMi0uOSAyLTJWN0g2djEyek0xOSA0aC0zLjVsLTEtMWgtNWwtMSAxSDV2MmgxNFY0eiIgLz4KPC9zdmc+Cg==);
  --jp-icon-download: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE5IDloLTRWM0g5djZINWw3IDcgNy03ek01IDE4djJoMTR2LTJINXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-duplicate: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiIGNsaXAtcnVsZT0iZXZlbm9kZCIgZD0iTTIuNzk5OTggMC44NzVIOC44OTU4MkM5LjIwMDYxIDAuODc1IDkuNDQ5OTggMS4xMzkxNCA5LjQ0OTk4IDEuNDYxOThDOS40NDk5OCAxLjc4NDgyIDkuMjAwNjEgMi4wNDg5NiA4Ljg5NTgyIDIuMDQ4OTZIMy4zNTQxNUMzLjA0OTM2IDIuMDQ4OTYgMi43OTk5OCAyLjMxMzEgMi43OTk5OCAyLjYzNTk0VjkuNjc5NjlDMi43OTk5OCAxMC4wMDI1IDIuNTUwNjEgMTAuMjY2NyAyLjI0NTgyIDEwLjI2NjdDMS45NDEwMyAxMC4yNjY3IDEuNjkxNjUgMTAuMDAyNSAxLjY5MTY1IDkuNjc5NjlWMi4wNDg5NkMxLjY5MTY1IDEuNDAzMjggMi4xOTA0IDAuODc1IDIuNzk5OTggMC44NzVaTTUuMzY2NjUgMTEuOVY0LjU1SDExLjA4MzNWMTEuOUg1LjM2NjY1Wk00LjE0MTY1IDQuMTQxNjdDNC4xNDE2NSAzLjY5MDYzIDQuNTA3MjggMy4zMjUgNC45NTgzMiAzLjMyNUgxMS40OTE3QzExLjk0MjcgMy4zMjUgMTIuMzA4MyAzLjY5MDYzIDEyLjMwODMgNC4xNDE2N1YxMi4zMDgzQzEyLjMwODMgMTIuNzU5NCAxMS45NDI3IDEzLjEyNSAxMS40OTE3IDEzLjEyNUg0Ljk1ODMyQzQuNTA3MjggMTMuMTI1IDQuMTQxNjUgMTIuNzU5NCA0LjE0MTY1IDEyLjMwODNWNC4xNDE2N1oiIGZpbGw9IiM2MTYxNjEiLz4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNOS40MzU3NCA4LjI2NTA3SDguMzY0MzFWOS4zMzY1QzguMzY0MzEgOS40NTQzNSA4LjI2Nzg4IDkuNTUwNzggOC4xNTAwMiA5LjU1MDc4QzguMDMyMTcgOS41NTA3OCA3LjkzNTc0IDkuNDU0MzUgNy45MzU3NCA5LjMzNjVWOC4yNjUwN0g2Ljg2NDMxQzYuNzQ2NDUgOC4yNjUwNyA2LjY1MDAyIDguMTY4NjQgNi42NTAwMiA4LjA1MDc4QzYuNjUwMDIgNy45MzI5MiA2Ljc0NjQ1IDcuODM2NSA2Ljg2NDMxIDcuODM2NUg3LjkzNTc0VjYuNzY1MDdDNy45MzU3NCA2LjY0NzIxIDguMDMyMTcgNi41NTA3OCA4LjE1MDAyIDYuNTUwNzhDOC4yNjc4OCA2LjU1MDc4IDguMzY0MzEgNi42NDcyMSA4LjM2NDMxIDYuNzY1MDdWNy44MzY1SDkuNDM1NzRDOS41NTM2IDcuODM2NSA5LjY1MDAyIDcuOTMyOTIgOS42NTAwMiA4LjA1MDc4QzkuNjUwMDIgOC4xNjg2NCA5LjU1MzYgOC4yNjUwNyA5LjQzNTc0IDguMjY1MDdaIiBmaWxsPSIjNjE2MTYxIiBzdHJva2U9IiM2MTYxNjEiIHN0cm9rZS13aWR0aD0iMC41Ii8+Cjwvc3ZnPgo=);
  --jp-icon-edit: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMgMTcuMjVWMjFoMy43NUwxNy44MSA5Ljk0bC0zLjc1LTMuNzVMMyAxNy4yNXpNMjAuNzEgNy4wNGMuMzktLjM5LjM5LTEuMDIgMC0xLjQxbC0yLjM0LTIuMzRjLS4zOS0uMzktMS4wMi0uMzktMS40MSAwbC0xLjgzIDEuODMgMy43NSAzLjc1IDEuODMtMS44M3oiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-ellipses: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPGNpcmNsZSBjeD0iNSIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIyIi8+CiAgICA8Y2lyY2xlIGN4PSIxOSIgY3k9IjEyIiByPSIyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-error: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjE5IiByPSIyIi8+PHBhdGggZD0iTTEwIDNoNHYxMmgtNHoiLz48L2c+CjxwYXRoIGZpbGw9Im5vbmUiIGQ9Ik0wIDBoMjR2MjRIMHoiLz4KPC9zdmc+Cg==);
  --jp-icon-expand-all: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTggMmMxIDAgMTEgMCAxMiAwczIgMSAyIDJjMCAxIDAgMTEgMCAxMnMwIDItMiAyQzIwIDE0IDIwIDQgMjAgNFMxMCA0IDYgNGMwLTIgMS0yIDItMnoiIC8+CiAgICAgICAgPHBhdGgKICAgICAgICAgICAgZD0iTTE4IDhjMC0xLTEtMi0yLTJTNSA2IDQgNnMtMiAxLTIgMmMwIDEgMCAxMSAwIDEyczEgMiAyIDJjMSAwIDExIDAgMTIgMHMyLTEgMi0yYzAtMSAwLTExIDAtMTJ6bS0yIDB2MTJINFY4eiIgLz4KICAgICAgICA8cGF0aCBkPSJNMTEgMTBIOXYzSDZ2MmgzdjNoMnYtM2gzdi0yaC0zeiIgLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-extension: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwLjUgMTFIMTlWN2MwLTEuMS0uOS0yLTItMmgtNFYzLjVDMTMgMi4xMiAxMS44OCAxIDEwLjUgMVM4IDIuMTIgOCAzLjVWNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAydjMuOEgzLjVjMS40OSAwIDIuNyAxLjIxIDIuNyAyLjdzLTEuMjEgMi43LTIuNyAyLjdIMlYyMGMwIDEuMS45IDIgMiAyaDMuOHYtMS41YzAtMS40OSAxLjIxLTIuNyAyLjctMi43IDEuNDkgMCAyLjcgMS4yMSAyLjcgMi43VjIySDE3YzEuMSAwIDItLjkgMi0ydi00aDEuNWMxLjM4IDAgMi41LTEuMTIgMi41LTIuNVMyMS44OCAxMSAyMC41IDExeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-fast-forward: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTQgMThsOC41LTZMNCA2djEyem05LTEydjEybDguNS02TDEzIDZ6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-file-upload: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTkgMTZoNnYtNmg0bC03LTctNyA3aDR6bS00IDJoMTR2Mkg1eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-file: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuMyA4LjJsLTUuNS01LjVjLS4zLS4zLS43LS41LTEuMi0uNUgzLjljLS44LjEtMS42LjktMS42IDEuOHYxNC4xYzAgLjkuNyAxLjYgMS42IDEuNmgxNC4yYy45IDAgMS42LS43IDEuNi0xLjZWOS40Yy4xLS41LS4xLS45LS40LTEuMnptLTUuOC0zLjNsMy40IDMuNmgtMy40VjQuOXptMy45IDEyLjdINC43Yy0uMSAwLS4yIDAtLjItLjJWNC43YzAtLjIuMS0uMy4yLS4zaDcuMnY0LjRzMCAuOC4zIDEuMWMuMy4zIDEuMS4zIDEuMS4zaDQuM3Y3LjJzLS4xLjItLjIuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-filter-dot: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgogIDxnIGNsYXNzPSJqcC1pY29uLWRvdCIgZmlsbD0iI0ZGRiI+CiAgICA8Y2lyY2xlIGN4PSIxOCIgY3k9IjE3IiByPSIzIj48L2NpcmNsZT4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-filter-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEwIDE4aDR2LTJoLTR2MnpNMyA2djJoMThWNkgzem0zIDdoMTJ2LTJINnYyeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-filter: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiNGRkYiPgogICAgPHBhdGggZD0iTTE0LDEyVjE5Ljg4QzE0LjA0LDIwLjE4IDEzLjk0LDIwLjUgMTMuNzEsMjAuNzFDMTMuMzIsMjEuMSAxMi42OSwyMS4xIDEyLjMsMjAuNzFMMTAuMjksMTguN0MxMC4wNiwxOC40NyA5Ljk2LDE4LjE2IDEwLDE3Ljg3VjEySDkuOTdMNC4yMSw0LjYyQzMuODcsNC4xOSAzLjk1LDMuNTYgNC4zOCwzLjIyQzQuNTcsMy4wOCA0Ljc4LDMgNSwzVjNIMTlWM0MxOS4yMiwzIDE5LjQzLDMuMDggMTkuNjIsMy4yMkMyMC4wNSwzLjU2IDIwLjEzLDQuMTkgMTkuNzksNC42MkwxNC4wMywxMkgxNFoiIC8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-folder-favorite: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgwVjB6IiBmaWxsPSJub25lIi8+PHBhdGggY2xhc3M9ImpwLWljb24zIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxNjE2MSIgZD0iTTIwIDZoLThsLTItMkg0Yy0xLjEgMC0yIC45LTIgMnYxMmMwIDEuMS45IDIgMiAyaDE2YzEuMSAwIDItLjkgMi0yVjhjMC0xLjEtLjktMi0yLTJ6bS0yLjA2IDExTDE1IDE1LjI4IDEyLjA2IDE3bC43OC0zLjMzLTIuNTktMi4yNCAzLjQxLS4yOUwxNSA4bDEuMzQgMy4xNCAzLjQxLjI5LTIuNTkgMi4yNC43OCAzLjMzeiIvPgo8L3N2Zz4K);
  --jp-icon-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY4YzAtMS4xLS45LTItMi0yaC04bC0yLTJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-home: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjRweCIgdmlld0JveD0iMCAwIDI0IDI0IiB3aWR0aD0iMjRweCIgZmlsbD0iIzAwMDAwMCI+CiAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPjxwYXRoIGNsYXNzPSJqcC1pY29uMyBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xMCAyMHYtNmg0djZoNXYtOGgzTDEyIDMgMiAxMmgzdjh6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-html5: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uMCBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiMwMDAiIGQ9Ik0xMDguNCAwaDIzdjIyLjhoMjEuMlYwaDIzdjY5aC0yM1Y0NmgtMjF2MjNoLTIzLjJNMjA2IDIzaC0yMC4zVjBoNjMuN3YyM0gyMjl2NDZoLTIzbTUzLjUtNjloMjQuMWwxNC44IDI0LjNMMzEzLjIgMGgyNC4xdjY5aC0yM1YzNC44bC0xNi4xIDI0LjgtMTYuMS0yNC44VjY5aC0yMi42bTg5LjItNjloMjN2NDYuMmgzMi42VjY5aC01NS42Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2U0NGQyNiIgZD0iTTEwNy42IDQ3MWwtMzMtMzcwLjRoMzYyLjhsLTMzIDM3MC4yTDI1NS43IDUxMiIvPgogIDxwYXRoIGNsYXNzPSJqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNmMTY1MjkiIGQ9Ik0yNTYgNDgwLjVWMTMxaDE0OC4zTDM3NiA0NDciLz4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNlYmViZWIiIGQ9Ik0xNDIgMTc2LjNoMTE0djQ1LjRoLTY0LjJsNC4yIDQ2LjVoNjB2NDUuM0gxNTQuNG0yIDIyLjhIMjAybDMuMiAzNi4zIDUwLjggMTMuNnY0Ny40bC05My4yLTI2Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZS1pbnZlcnNlIiBmaWxsPSIjZmZmIiBkPSJNMzY5LjYgMTc2LjNIMjU1Ljh2NDUuNGgxMDkuNm0tNC4xIDQ2LjVIMjU1Ljh2NDUuNGg1NmwtNS4zIDU5LTUwLjcgMTMuNnY0Ny4ybDkzLTI1LjgiLz4KPC9zdmc+Cg==);
  --jp-icon-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1icmFuZDQganAtaWNvbi1zZWxlY3RhYmxlLWludmVyc2UiIGZpbGw9IiNGRkYiIGQ9Ik0yLjIgMi4yaDE3LjV2MTcuNUgyLjJ6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzNGNTFCNSIgZD0iTTIuMiAyLjJ2MTcuNWgxNy41bC4xLTE3LjVIMi4yem0xMi4xIDIuMmMxLjIgMCAyLjIgMSAyLjIgMi4ycy0xIDIuMi0yLjIgMi4yLTIuMi0xLTIuMi0yLjIgMS0yLjIgMi4yLTIuMnpNNC40IDE3LjZsMy4zLTguOCAzLjMgNi42IDIuMi0zLjIgNC40IDUuNEg0LjR6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-info: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUwLjk3OCA1MC45NzgiPgoJPGcgY2xhc3M9ImpwLWljb24zIiBmaWxsPSIjNjE2MTYxIj4KCQk8cGF0aCBkPSJNNDMuNTIsNy40NThDMzguNzExLDIuNjQ4LDMyLjMwNywwLDI1LjQ4OSwwQzE4LjY3LDAsMTIuMjY2LDIuNjQ4LDcuNDU4LDcuNDU4CgkJCWMtOS45NDMsOS45NDEtOS45NDMsMjYuMTE5LDAsMzYuMDYyYzQuODA5LDQuODA5LDExLjIxMiw3LjQ1NiwxOC4wMzEsNy40NThjMCwwLDAuMDAxLDAsMC4wMDIsMAoJCQljNi44MTYsMCwxMy4yMjEtMi42NDgsMTguMDI5LTcuNDU4YzQuODA5LTQuODA5LDcuNDU3LTExLjIxMiw3LjQ1Ny0xOC4wM0M1MC45NzcsMTguNjcsNDguMzI4LDEyLjI2Niw0My41Miw3LjQ1OHoKCQkJIE00Mi4xMDYsNDIuMTA1Yy00LjQzMiw0LjQzMS0xMC4zMzIsNi44NzItMTYuNjE1LDYuODcyaC0wLjAwMmMtNi4yODUtMC4wMDEtMTIuMTg3LTIuNDQxLTE2LjYxNy02Ljg3MgoJCQljLTkuMTYyLTkuMTYzLTkuMTYyLTI0LjA3MSwwLTMzLjIzM0MxMy4zMDMsNC40NCwxOS4yMDQsMiwyNS40ODksMmM2LjI4NCwwLDEyLjE4NiwyLjQ0LDE2LjYxNyw2Ljg3MgoJCQljNC40MzEsNC40MzEsNi44NzEsMTAuMzMyLDYuODcxLDE2LjYxN0M0OC45NzcsMzEuNzcyLDQ2LjUzNiwzNy42NzUsNDIuMTA2LDQyLjEwNXoiLz4KCQk8cGF0aCBkPSJNMjMuNTc4LDMyLjIxOGMtMC4wMjMtMS43MzQsMC4xNDMtMy4wNTksMC40OTYtMy45NzJjMC4zNTMtMC45MTMsMS4xMS0xLjk5NywyLjI3Mi0zLjI1MwoJCQljMC40NjgtMC41MzYsMC45MjMtMS4wNjIsMS4zNjctMS41NzVjMC42MjYtMC43NTMsMS4xMDQtMS40NzgsMS40MzYtMi4xNzVjMC4zMzEtMC43MDcsMC40OTUtMS41NDEsMC40OTUtMi41CgkJCWMwLTEuMDk2LTAuMjYtMi4wODgtMC43NzktMi45NzljLTAuNTY1LTAuODc5LTEuNTAxLTEuMzM2LTIuODA2LTEuMzY5Yy0xLjgwMiwwLjA1Ny0yLjk4NSwwLjY2Ny0zLjU1LDEuODMyCgkJCWMtMC4zMDEsMC41MzUtMC41MDMsMS4xNDEtMC42MDcsMS44MTRjLTAuMTM5LDAuNzA3LTAuMjA3LDEuNDMyLTAuMjA3LDIuMTc0aC0yLjkzN2MtMC4wOTEtMi4yMDgsMC40MDctNC4xMTQsMS40OTMtNS43MTkKCQkJYzEuMDYyLTEuNjQsMi44NTUtMi40ODEsNS4zNzgtMi41MjdjMi4xNiwwLjAyMywzLjg3NCwwLjYwOCw1LjE0MSwxLjc1OGMxLjI3OCwxLjE2LDEuOTI5LDIuNzY0LDEuOTUsNC44MTEKCQkJYzAsMS4xNDItMC4xMzcsMi4xMTEtMC40MSwyLjkxMWMtMC4zMDksMC44NDUtMC43MzEsMS41OTMtMS4yNjgsMi4yNDNjLTAuNDkyLDAuNjUtMS4wNjgsMS4zMTgtMS43MywyLjAwMgoJCQljLTAuNjUsMC42OTctMS4zMTMsMS40NzktMS45ODcsMi4zNDZjLTAuMjM5LDAuMzc3LTAuNDI5LDAuNzc3LTAuNTY1LDEuMTk5Yy0wLjE2LDAuOTU5LTAuMjE3LDEuOTUxLTAuMTcxLDIuOTc5CgkJCUMyNi41ODksMzIuMjE4LDIzLjU3OCwzMi4yMTgsMjMuNTc4LDMyLjIxOHogTTIzLjU3OCwzOC4yMnYtMy40ODRoMy4wNzZ2My40ODRIMjMuNTc4eiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-inspector: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaW5zcGVjdG9yLWljb24tY29sb3IganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNEg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMThjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY2YzAtMS4xLS45LTItMi0yem0tNSAxNEg0di00aDExdjR6bTAtNUg0VjloMTF2NHptNSA1aC00VjloNHY5eiIvPgo8L3N2Zz4K);
  --jp-icon-json: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtanNvbi1pY29uLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0Y5QTgyNSI+CiAgICA8cGF0aCBkPSJNMjAuMiAxMS44Yy0xLjYgMC0xLjcuNS0xLjcgMSAwIC40LjEuOS4xIDEuMy4xLjUuMS45LjEgMS4zIDAgMS43LTEuNCAyLjMtMy41IDIuM2gtLjl2LTEuOWguNWMxLjEgMCAxLjQgMCAxLjQtLjggMC0uMyAwLS42LS4xLTEgMC0uNC0uMS0uOC0uMS0xLjIgMC0xLjMgMC0xLjggMS4zLTItMS4zLS4yLTEuMy0uNy0xLjMtMiAwLS40LjEtLjguMS0xLjIuMS0uNC4xLS43LjEtMSAwLS44LS40LS43LTEuNC0uOGgtLjVWNC4xaC45YzIuMiAwIDMuNS43IDMuNSAyLjMgMCAuNC0uMS45LS4xIDEuMy0uMS41LS4xLjktLjEgMS4zIDAgLjUuMiAxIDEuNyAxdjEuOHpNMS44IDEwLjFjMS42IDAgMS43LS41IDEuNy0xIDAtLjQtLjEtLjktLjEtMS4zLS4xLS41LS4xLS45LS4xLTEuMyAwLTEuNiAxLjQtMi4zIDMuNS0yLjNoLjl2MS45aC0uNWMtMSAwLTEuNCAwLTEuNC44IDAgLjMgMCAuNi4xIDEgMCAuMi4xLjYuMSAxIDAgMS4zIDAgMS44LTEuMyAyQzYgMTEuMiA2IDExLjcgNiAxM2MwIC40LS4xLjgtLjEgMS4yLS4xLjMtLjEuNy0uMSAxIDAgLjguMy44IDEuNC44aC41djEuOWgtLjljLTIuMSAwLTMuNS0uNi0zLjUtMi4zIDAtLjQuMS0uOS4xLTEuMy4xLS41LjEtLjkuMS0xLjMgMC0uNS0uMi0xLTEuNy0xdi0xLjl6Ii8+CiAgICA8Y2lyY2xlIGN4PSIxMSIgY3k9IjEzLjgiIHI9IjIuMSIvPgogICAgPGNpcmNsZSBjeD0iMTEiIGN5PSI4LjIiIHI9IjIuMSIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-julia: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDMyNSAzMDAiPgogIDxnIGNsYXNzPSJqcC1icmFuZDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjY2IzYzMzIj4KICAgIDxwYXRoIGQ9Ik0gMTUwLjg5ODQzOCAyMjUgQyAxNTAuODk4NDM4IDI2Ni40MjE4NzUgMTE3LjMyMDMxMiAzMDAgNzUuODk4NDM4IDMwMCBDIDM0LjQ3NjU2MiAzMDAgMC44OTg0MzggMjY2LjQyMTg3NSAwLjg5ODQzOCAyMjUgQyAwLjg5ODQzOCAxODMuNTc4MTI1IDM0LjQ3NjU2MiAxNTAgNzUuODk4NDM4IDE1MCBDIDExNy4zMjAzMTIgMTUwIDE1MC44OTg0MzggMTgzLjU3ODEyNSAxNTAuODk4NDM4IDIyNSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzM4OTgyNiI+CiAgICA8cGF0aCBkPSJNIDIzNy41IDc1IEMgMjM3LjUgMTE2LjQyMTg3NSAyMDMuOTIxODc1IDE1MCAxNjIuNSAxNTAgQyAxMjEuMDc4MTI1IDE1MCA4Ny41IDExNi40MjE4NzUgODcuNSA3NSBDIDg3LjUgMzMuNTc4MTI1IDEyMS4wNzgxMjUgMCAxNjIuNSAwIEMgMjAzLjkyMTg3NSAwIDIzNy41IDMzLjU3ODEyNSAyMzcuNSA3NSIvPgogIDwvZz4KICA8ZyBjbGFzcz0ianAtYnJhbmQwIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzk1NThiMiI+CiAgICA8cGF0aCBkPSJNIDMyNC4xMDE1NjIgMjI1IEMgMzI0LjEwMTU2MiAyNjYuNDIxODc1IDI5MC41MjM0MzggMzAwIDI0OS4xMDE1NjIgMzAwIEMgMjA3LjY3OTY4OCAzMDAgMTc0LjEwMTU2MiAyNjYuNDIxODc1IDE3NC4xMDE1NjIgMjI1IEMgMTc0LjEwMTU2MiAxODMuNTc4MTI1IDIwNy42Nzk2ODggMTUwIDI0OS4xMDE1NjIgMTUwIEMgMjkwLjUyMzQzOCAxNTAgMzI0LjEwMTU2MiAxODMuNTc4MTI1IDMyNC4xMDE1NjIgMjI1Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-jupyter-favicon: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTUyIiBoZWlnaHQ9IjE2NSIgdmlld0JveD0iMCAwIDE1MiAxNjUiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgPGcgY2xhc3M9ImpwLWp1cHl0ZXItaWNvbi1jb2xvciIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA3ODk0NywgMTEwLjU4MjkyNykiIGQ9Ik03NS45NDIyODQyLDI5LjU4MDQ1NjEgQzQzLjMwMjM5NDcsMjkuNTgwNDU2MSAxNC43OTY3ODMyLDE3LjY1MzQ2MzQgMCwwIEM1LjUxMDgzMjExLDE1Ljg0MDY4MjkgMTUuNzgxNTM4OSwyOS41NjY3NzMyIDI5LjM5MDQ5NDcsMzkuMjc4NDE3MSBDNDIuOTk5Nyw0OC45ODk4NTM3IDU5LjI3MzcsNTQuMjA2NzgwNSA3NS45NjA1Nzg5LDU0LjIwNjc4MDUgQzkyLjY0NzQ1NzksNTQuMjA2NzgwNSAxMDguOTIxNDU4LDQ4Ljk4OTg1MzcgMTIyLjUzMDY2MywzOS4yNzg0MTcxIEMxMzYuMTM5NDUzLDI5LjU2Njc3MzIgMTQ2LjQxMDI4NCwxNS44NDA2ODI5IDE1MS45MjExNTgsMCBDMTM3LjA4Nzg2OCwxNy42NTM0NjM0IDEwOC41ODI1ODksMjkuNTgwNDU2MSA3NS45NDIyODQyLDI5LjU4MDQ1NjEgTDc1Ljk0MjI4NDIsMjkuNTgwNDU2MSBaIiAvPgogICAgPHBhdGggdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMzczNjgsIDAuNzA0ODc4KSIgZD0iTTc1Ljk3ODQ1NzksMjQuNjI2NDA3MyBDMTA4LjYxODc2MywyNC42MjY0MDczIDEzNy4xMjQ0NTgsMzYuNTUzNDQxNSAxNTEuOTIxMTU4LDU0LjIwNjc4MDUgQzE0Ni40MTAyODQsMzguMzY2MjIyIDEzNi4xMzk0NTMsMjQuNjQwMTMxNyAxMjIuNTMwNjYzLDE0LjkyODQ4NzggQzEwOC45MjE0NTgsNS4yMTY4NDM5IDkyLjY0NzQ1NzksMCA3NS45NjA1Nzg5LDAgQzU5LjI3MzcsMCA0Mi45OTk3LDUuMjE2ODQzOSAyOS4zOTA0OTQ3LDE0LjkyODQ4NzggQzE1Ljc4MTUzODksMjQuNjQwMTMxNyA1LjUxMDgzMjExLDM4LjM2NjIyMiAwLDU0LjIwNjc4MDUgQzE0LjgzMzA4MTYsMzYuNTg5OTI5MyA0My4zMzg1Njg0LDI0LjYyNjQwNzMgNzUuOTc4NDU3OSwyNC42MjY0MDczIEw3NS45Nzg0NTc5LDI0LjYyNjQwNzMgWiIgLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-jupyter: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzkiIGhlaWdodD0iNTEiIHZpZXdCb3g9IjAgMCAzOSA1MSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMTYzOCAtMjI4MSkiPgogICAgIDxnIGNsYXNzPSJqcC1qdXB5dGVyLWljb24tY29sb3IiIGZpbGw9IiNGMzc3MjYiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5Ljc0IDIzMTEuOTgpIiBkPSJNIDE4LjI2NDYgNy4xMzQxMUMgMTAuNDE0NSA3LjEzNDExIDMuNTU4NzIgNC4yNTc2IDAgMEMgMS4zMjUzOSAzLjgyMDQgMy43OTU1NiA3LjEzMDgxIDcuMDY4NiA5LjQ3MzAzQyAxMC4zNDE3IDExLjgxNTIgMTQuMjU1NyAxMy4wNzM0IDE4LjI2OSAxMy4wNzM0QyAyMi4yODIzIDEzLjA3MzQgMjYuMTk2MyAxMS44MTUyIDI5LjQ2OTQgOS40NzMwM0MgMzIuNzQyNCA3LjEzMDgxIDM1LjIxMjYgMy44MjA0IDM2LjUzOCAwQyAzMi45NzA1IDQuMjU3NiAyNi4xMTQ4IDcuMTM0MTEgMTguMjY0NiA3LjEzNDExWiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM5LjczIDIyODUuNDgpIiBkPSJNIDE4LjI3MzMgNS45MzkzMUMgMjYuMTIzNSA1LjkzOTMxIDMyLjk3OTMgOC44MTU4MyAzNi41MzggMTMuMDczNEMgMzUuMjEyNiA5LjI1MzAzIDMyLjc0MjQgNS45NDI2MiAyOS40Njk0IDMuNjAwNEMgMjYuMTk2MyAxLjI1ODE4IDIyLjI4MjMgMCAxOC4yNjkgMEMgMTQuMjU1NyAwIDEwLjM0MTcgMS4yNTgxOCA3LjA2ODYgMy42MDA0QyAzLjc5NTU2IDUuOTQyNjIgMS4zMjUzOSA5LjI1MzAzIDAgMTMuMDczNEMgMy41Njc0NSA4LjgyNDYzIDEwLjQyMzIgNS45MzkzMSAxOC4yNzMzIDUuOTM5MzFaIi8+CiAgICA8L2c+CiAgICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjY5LjMgMjI4MS4zMSkiIGQ9Ik0gNS44OTM1MyAyLjg0NEMgNS45MTg4OSAzLjQzMTY1IDUuNzcwODUgNC4wMTM2NyA1LjQ2ODE1IDQuNTE2NDVDIDUuMTY1NDUgNS4wMTkyMiA0LjcyMTY4IDUuNDIwMTUgNC4xOTI5OSA1LjY2ODUxQyAzLjY2NDMgNS45MTY4OCAzLjA3NDQ0IDYuMDAxNTEgMi40OTgwNSA1LjkxMTcxQyAxLjkyMTY2IDUuODIxOSAxLjM4NDYzIDUuNTYxNyAwLjk1NDg5OCA1LjE2NDAxQyAwLjUyNTE3IDQuNzY2MzMgMC4yMjIwNTYgNC4yNDkwMyAwLjA4MzkwMzcgMy42Nzc1N0MgLTAuMDU0MjQ4MyAzLjEwNjExIC0wLjAyMTIzIDIuNTA2MTcgMC4xNzg3ODEgMS45NTM2NEMgMC4zNzg3OTMgMS40MDExIDAuNzM2ODA5IDAuOTIwODE3IDEuMjA3NTQgMC41NzM1MzhDIDEuNjc4MjYgMC4yMjYyNTkgMi4yNDA1NSAwLjAyNzU5MTkgMi44MjMyNiAwLjAwMjY3MjI5QyAzLjYwMzg5IC0wLjAzMDcxMTUgNC4zNjU3MyAwLjI0OTc4OSA0Ljk0MTQyIDAuNzgyNTUxQyA1LjUxNzExIDEuMzE1MzEgNS44NTk1NiAyLjA1Njc2IDUuODkzNTMgMi44NDRaIi8+CiAgICAgIDxwYXRoIHRyYW5zZm9ybT0idHJhbnNsYXRlKDE2MzkuOCAyMzIzLjgxKSIgZD0iTSA3LjQyNzg5IDMuNTgzMzhDIDcuNDYwMDggNC4zMjQzIDcuMjczNTUgNS4wNTgxOSA2Ljg5MTkzIDUuNjkyMTNDIDYuNTEwMzEgNi4zMjYwNyA1Ljk1MDc1IDYuODMxNTYgNS4yODQxMSA3LjE0NDZDIDQuNjE3NDcgNy40NTc2MyAzLjg3MzcxIDcuNTY0MTQgMy4xNDcwMiA3LjQ1MDYzQyAyLjQyMDMyIDcuMzM3MTIgMS43NDMzNiA3LjAwODcgMS4yMDE4NCA2LjUwNjk1QyAwLjY2MDMyOCA2LjAwNTIgMC4yNzg2MSA1LjM1MjY4IDAuMTA1MDE3IDQuNjMyMDJDIC0wLjA2ODU3NTcgMy45MTEzNSAtMC4wMjYyMzYxIDMuMTU0OTQgMC4yMjY2NzUgMi40NTg1NkMgMC40Nzk1ODcgMS43NjIxNyAwLjkzMTY5NyAxLjE1NzEzIDEuNTI1NzYgMC43MjAwMzNDIDIuMTE5ODMgMC4yODI5MzUgMi44MjkxNCAwLjAzMzQzOTUgMy41NjM4OSAwLjAwMzEzMzQ0QyA0LjU0NjY3IC0wLjAzNzQwMzMgNS41MDUyOSAwLjMxNjcwNiA2LjIyOTYxIDAuOTg3ODM1QyA2Ljk1MzkzIDEuNjU4OTYgNy4zODQ4NCAyLjU5MjM1IDcuNDI3ODkgMy41ODMzOEwgNy40Mjc4OSAzLjU4MzM4WiIvPgogICAgICA8cGF0aCB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxNjM4LjM2IDIyODYuMDYpIiBkPSJNIDIuMjc0NzEgNC4zOTYyOUMgMS44NDM2MyA0LjQxNTA4IDEuNDE2NzEgNC4zMDQ0NSAxLjA0Nzk5IDQuMDc4NDNDIDAuNjc5MjY4IDMuODUyNCAwLjM4NTMyOCAzLjUyMTE0IDAuMjAzMzcxIDMuMTI2NTZDIDAuMDIxNDEzNiAyLjczMTk4IC0wLjA0MDM3OTggMi4yOTE4MyAwLjAyNTgxMTYgMS44NjE4MUMgMC4wOTIwMDMxIDEuNDMxOCAwLjI4MzIwNCAxLjAzMTI2IDAuNTc1MjEzIDAuNzEwODgzQyAwLjg2NzIyMiAwLjM5MDUxIDEuMjQ2OTEgMC4xNjQ3MDggMS42NjYyMiAwLjA2MjA1OTJDIDIuMDg1NTMgLTAuMDQwNTg5NyAyLjUyNTYxIC0wLjAxNTQ3MTQgMi45MzA3NiAwLjEzNDIzNUMgMy4zMzU5MSAwLjI4Mzk0MSAzLjY4NzkyIDAuNTUxNTA1IDMuOTQyMjIgMC45MDMwNkMgNC4xOTY1MiAxLjI1NDYyIDQuMzQxNjkgMS42NzQzNiA0LjM1OTM1IDIuMTA5MTZDIDQuMzgyOTkgMi42OTEwNyA0LjE3Njc4IDMuMjU4NjkgMy43ODU5NyAzLjY4NzQ2QyAzLjM5NTE2IDQuMTE2MjQgMi44NTE2NiA0LjM3MTE2IDIuMjc0NzEgNC4zOTYyOUwgMi4yNzQ3MSA0LjM5NjI5WiIvPgogICAgPC9nPgogIDwvZz4+Cjwvc3ZnPgo=);
  --jp-icon-jupyterlab-wordmark: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIHZpZXdCb3g9IjAgMCAxODYwLjggNDc1Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0RTRFNEUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDQ4MC4xMzY0MDEsIDY0LjI3MTQ5MykiPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC4wMDAwMDAsIDU4Ljg3NTU2NikiPgogICAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwLjA4NzYwMywgMC4xNDAyOTQpIj4KICAgICAgICA8cGF0aCBkPSJNLTQyNi45LDE2OS44YzAsNDguNy0zLjcsNjQuNy0xMy42LDc2LjRjLTEwLjgsMTAtMjUsMTUuNS0zOS43LDE1LjVsMy43LDI5IGMyMi44LDAuMyw0NC44LTcuOSw2MS45LTIzLjFjMTcuOC0xOC41LDI0LTQ0LjEsMjQtODMuM1YwSC00Mjd2MTcwLjFMLTQyNi45LDE2OS44TC00MjYuOSwxNjkuOHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTU1LjA0NTI5NiwgNTYuODM3MTA0KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuNTYyNDUzLCAxLjc5OTg0MikiPgogICAgICAgIDxwYXRoIGQ9Ik0tMzEyLDE0OGMwLDIxLDAsMzkuNSwxLjcsNTUuNGgtMzEuOGwtMi4xLTMzLjNoLTAuOGMtNi43LDExLjYtMTYuNCwyMS4zLTI4LDI3LjkgYy0xMS42LDYuNi0yNC44LDEwLTM4LjIsOS44Yy0zMS40LDAtNjktMTcuNy02OS04OVYwaDM2LjR2MTEyLjdjMCwzOC43LDExLjYsNjQuNyw0NC42LDY0LjdjMTAuMy0wLjIsMjAuNC0zLjUsMjguOS05LjQgYzguNS01LjksMTUuMS0xNC4zLDE4LjktMjMuOWMyLjItNi4xLDMuMy0xMi41LDMuMy0xOC45VjAuMmgzNi40VjE0OEgtMzEyTC0zMTIsMTQ4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgzOTAuMDEzMzIyLCA1My40Nzk2MzgpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS43MDY0NTgsIDAuMjMxNDI1KSI+CiAgICAgICAgPHBhdGggZD0iTS00NzguNiw3MS40YzAtMjYtMC44LTQ3LTEuNy02Ni43aDMyLjdsMS43LDM0LjhoMC44YzcuMS0xMi41LDE3LjUtMjIuOCwzMC4xLTI5LjcgYzEyLjUtNywyNi43LTEwLjMsNDEtOS44YzQ4LjMsMCw4NC43LDQxLjcsODQuNywxMDMuM2MwLDczLjEtNDMuNywxMDkuMi05MSwxMDkuMmMtMTIuMSwwLjUtMjQuMi0yLjItMzUtNy44IGMtMTAuOC01LjYtMTkuOS0xMy45LTI2LjYtMjQuMmgtMC44VjI5MWgtMzZ2LTIyMEwtNDc4LjYsNzEuNEwtNDc4LjYsNzEuNHogTS00NDIuNiwxMjUuNmMwLjEsNS4xLDAuNiwxMC4xLDEuNywxNS4xIGMzLDEyLjMsOS45LDIzLjMsMTkuOCwzMS4xYzkuOSw3LjgsMjIuMSwxMi4xLDM0LjcsMTIuMWMzOC41LDAsNjAuNy0zMS45LDYwLjctNzguNWMwLTQwLjctMjEuMS03NS42LTU5LjUtNzUuNiBjLTEyLjksMC40LTI1LjMsNS4xLTM1LjMsMTMuNGMtOS45LDguMy0xNi45LDE5LjctMTkuNiwzMi40Yy0xLjUsNC45LTIuMywxMC0yLjUsMTUuMVYxMjUuNkwtNDQyLjYsMTI1LjZMLTQ0Mi42LDEyNS42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSg2MDYuNzQwNzI2LCA1Ni44MzcxMDQpIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMC43NTEyMjYsIDEuOTg5Mjk5KSI+CiAgICAgICAgPHBhdGggZD0iTS00NDAuOCwwbDQzLjcsMTIwLjFjNC41LDEzLjQsOS41LDI5LjQsMTIuOCw0MS43aDAuOGMzLjctMTIuMiw3LjktMjcuNywxMi44LTQyLjQgbDM5LjctMTE5LjJoMzguNUwtMzQ2LjksMTQ1Yy0yNiw2OS43LTQzLjcsMTA1LjQtNjguNiwxMjcuMmMtMTIuNSwxMS43LTI3LjksMjAtNDQuNiwyMy45bC05LjEtMzEuMSBjMTEuNy0zLjksMjIuNS0xMC4xLDMxLjgtMTguMWMxMy4yLTExLjEsMjMuNy0yNS4yLDMwLjYtNDEuMmMxLjUtMi44LDIuNS01LjcsMi45LTguOGMtMC4zLTMuMy0xLjItNi42LTIuNS05LjdMLTQ4MC4yLDAuMSBoMzkuN0wtNDQwLjgsMEwtNDQwLjgsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoODIyLjc0ODEwNCwgMC4wMDAwMDApIj4KICAgICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMS40NjQwNTAsIDAuMzc4OTE0KSI+CiAgICAgICAgPHBhdGggZD0iTS00MTMuNywwdjU4LjNoNTJ2MjguMmgtNTJWMTk2YzAsMjUsNywzOS41LDI3LjMsMzkuNWM3LjEsMC4xLDE0LjItMC43LDIxLjEtMi41IGwxLjcsMjcuN2MtMTAuMywzLjctMjEuMyw1LjQtMzIuMiw1Yy03LjMsMC40LTE0LjYtMC43LTIxLjMtMy40Yy02LjgtMi43LTEyLjktNi44LTE3LjktMTIuMWMtMTAuMy0xMC45LTE0LjEtMjktMTQuMS01Mi45IFY4Ni41aC0zMVY1OC4zaDMxVjkuNkwtNDEzLjcsMEwtNDEzLjcsMHoiLz4KICAgICAgPC9nPgogICAgPC9nPgogICAgPGcgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOTc0LjQzMzI4NiwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuOTkwMDM0LCAwLjYxMDMzOSkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDQ1LjgsMTEzYzAuOCw1MCwzMi4yLDcwLjYsNjguNiw3MC42YzE5LDAuNiwzNy45LTMsNTUuMy0xMC41bDYuMiwyNi40IGMtMjAuOSw4LjktNDMuNSwxMy4xLTY2LjIsMTIuNmMtNjEuNSwwLTk4LjMtNDEuMi05OC4zLTEwMi41Qy00ODAuMiw0OC4yLTQ0NC43LDAtMzg2LjUsMGM2NS4yLDAsODIuNyw1OC4zLDgyLjcsOTUuNyBjLTAuMSw1LjgtMC41LDExLjUtMS4yLDE3LjJoLTE0MC42SC00NDUuOEwtNDQ1LjgsMTEzeiBNLTMzOS4yLDg2LjZjMC40LTIzLjUtOS41LTYwLjEtNTAuNC02MC4xIGMtMzYuOCwwLTUyLjgsMzQuNC01NS43LDYwLjFILTMzOS4yTC0zMzkuMiw4Ni42TC0zMzkuMiw4Ni42eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgICA8ZyB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMjAxLjk2MTA1OCwgNTMuNDc5NjM4KSI+CiAgICAgIDxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEuMTc5NjQwLCAwLjcwNTA2OCkiPgogICAgICAgIDxwYXRoIGQ9Ik0tNDc4LjYsNjhjMC0yMy45LTAuNC00NC41LTEuNy02My40aDMxLjhsMS4yLDM5LjloMS43YzkuMS0yNy4zLDMxLTQ0LjUsNTUuMy00NC41IGMzLjUtMC4xLDcsMC40LDEwLjMsMS4ydjM0LjhjLTQuMS0wLjktOC4yLTEuMy0xMi40LTEuMmMtMjUuNiwwLTQzLjcsMTkuNy00OC43LDQ3LjRjLTEsNS43LTEuNiwxMS41LTEuNywxNy4ydjEwOC4zaC0zNlY2OCBMLTQ3OC42LDY4eiIvPgogICAgICA8L2c+CiAgICA8L2c+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi13YXJuMCIgZmlsbD0iI0YzNzcyNiI+CiAgICA8cGF0aCBkPSJNMTM1Mi4zLDMyNi4yaDM3VjI4aC0zN1YzMjYuMnogTTE2MDQuOCwzMjYuMmMtMi41LTEzLjktMy40LTMxLjEtMy40LTQ4Ljd2LTc2IGMwLTQwLjctMTUuMS04My4xLTc3LjMtODMuMWMtMjUuNiwwLTUwLDcuMS02Ni44LDE4LjFsOC40LDI0LjRjMTQuMy05LjIsMzQtMTUuMSw1My0xNS4xYzQxLjYsMCw0Ni4yLDMwLjIsNDYuMiw0N3Y0LjIgYy03OC42LTAuNC0xMjIuMywyNi41LTEyMi4zLDc1LjZjMCwyOS40LDIxLDU4LjQsNjIuMiw1OC40YzI5LDAsNTAuOS0xNC4zLDYyLjItMzAuMmgxLjNsMi45LDI1LjZIMTYwNC44eiBNMTU2NS43LDI1Ny43IGMwLDMuOC0wLjgsOC0yLjEsMTEuOGMtNS45LDE3LjItMjIuNywzNC00OS4yLDM0Yy0xOC45LDAtMzQuOS0xMS4zLTM0LjktMzUuM2MwLTM5LjUsNDUuOC00Ni42LDg2LjItNDUuOFYyNTcuN3ogTTE2OTguNSwzMjYuMiBsMS43LTMzLjZoMS4zYzE1LjEsMjYuOSwzOC43LDM4LjIsNjguMSwzOC4yYzQ1LjQsMCw5MS4yLTM2LjEsOTEuMi0xMDguOGMwLjQtNjEuNy0zNS4zLTEwMy43LTg1LjctMTAzLjcgYy0zMi44LDAtNTYuMywxNC43LTY5LjMsMzcuNGgtMC44VjI4aC0zNi42djI0NS43YzAsMTguMS0wLjgsMzguNi0xLjcsNTIuNUgxNjk4LjV6IE0xNzA0LjgsMjA4LjJjMC01LjksMS4zLTEwLjksMi4xLTE1LjEgYzcuNi0yOC4xLDMxLjEtNDUuNCw1Ni4zLTQ1LjRjMzkuNSwwLDYwLjUsMzQuOSw2MC41LDc1LjZjMCw0Ni42LTIzLjEsNzguMS02MS44LDc4LjFjLTI2LjksMC00OC4zLTE3LjYtNTUuNS00My4zIGMtMC44LTQuMi0xLjctOC44LTEuNy0xMy40VjIwOC4yeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzYxNjE2MSIgZD0iTTE1IDlIOXY2aDZWOXptLTIgNGgtMnYtMmgydjJ6bTgtMlY5aC0yVjdjMC0xLjEtLjktMi0yLTJoLTJWM2gtMnYyaC0yVjNIOXYySDdjLTEuMSAwLTIgLjktMiAydjJIM3YyaDJ2MkgzdjJoMnYyYzAgMS4xLjkgMiAyIDJoMnYyaDJ2LTJoMnYyaDJ2LTJoMmMxLjEgMCAyLS45IDItMnYtMmgydi0yaC0ydi0yaDJ6bS00IDZIN1Y3aDEwdjEweiIvPgo8L3N2Zz4K);
  --jp-icon-keyboard: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMjAgNUg0Yy0xLjEgMC0xLjk5LjktMS45OSAyTDIgMTdjMCAxLjEuOSAyIDIgMmgxNmMxLjEgMCAyLS45IDItMlY3YzAtMS4xLS45LTItMi0yem0tOSAzaDJ2MmgtMlY4em0wIDNoMnYyaC0ydi0yek04IDhoMnYySDhWOHptMCAzaDJ2Mkg4di0yem0tMSAySDV2LTJoMnYyem0wLTNINVY4aDJ2MnptOSA3SDh2LTJoOHYyem0wLTRoLTJ2LTJoMnYyem0wLTNoLTJWOGgydjJ6bTMgM2gtMnYtMmgydjJ6bTAtM2gtMlY4aDJ2MnoiLz4KPC9zdmc+Cg==);
  --jp-icon-launch: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMzIgMzIiIHdpZHRoPSIzMiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik0yNiwyOEg2YTIuMDAyNywyLjAwMjcsMCwwLDEtMi0yVjZBMi4wMDI3LDIuMDAyNywwLDAsMSw2LDRIMTZWNkg2VjI2SDI2VjE2aDJWMjZBMi4wMDI3LDIuMDAyNywwLDAsMSwyNiwyOFoiLz4KICAgIDxwb2x5Z29uIHBvaW50cz0iMjAgMiAyMCA0IDI2LjU4NiA0IDE4IDEyLjU4NiAxOS40MTQgMTQgMjggNS40MTQgMjggMTIgMzAgMTIgMzAgMiAyMCAyIi8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-launcher: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkgMTlINVY1aDdWM0g1YTIgMiAwIDAwLTIgMnYxNGEyIDIgMCAwMDIgMmgxNGMxLjEgMCAyLS45IDItMnYtN2gtMnY3ek0xNCAzdjJoMy41OWwtOS44MyA5LjgzIDEuNDEgMS40MUwxOSA2LjQxVjEwaDJWM2gtN3oiLz4KPC9zdmc+Cg==);
  --jp-icon-line-form: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGZpbGw9IndoaXRlIiBkPSJNNS44OCA0LjEyTDEzLjc2IDEybC03Ljg4IDcuODhMOCAyMmwxMC0xMEw4IDJ6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-link: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTMuOSAxMmMwLTEuNzEgMS4zOS0zLjEgMy4xLTMuMWg0VjdIN2MtMi43NiAwLTUgMi4yNC01IDVzMi4yNCA1IDUgNWg0di0xLjlIN2MtMS43MSAwLTMuMS0xLjM5LTMuMS0zLjF6TTggMTNoOHYtMkg4djJ6bTktNmgtNHYxLjloNGMxLjcxIDAgMy4xIDEuMzkgMy4xIDMuMXMtMS4zOSAzLjEtMy4xIDMuMWgtNFYxN2g0YzIuNzYgMCA1LTIuMjQgNS01cy0yLjI0LTUtNS01eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-list: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xOSA1djE0SDVWNWgxNG0xLjEtMkgzLjljLS41IDAtLjkuNC0uOS45djE2LjJjMCAuNC40LjkuOS45aDE2LjJjLjQgMCAuOS0uNS45LS45VjMuOWMwLS41LS41LS45LS45LS45ek0xMSA3aDZ2MmgtNlY3em0wIDRoNnYyaC02di0yem0wIDRoNnYyaC02ek03IDdoMnYySDd6bTAgNGgydjJIN3ptMCA0aDJ2Mkg3eiIvPgo8L3N2Zz4K);
  --jp-icon-markdown: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDAganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjN0IxRkEyIiBkPSJNNSAxNC45aDEybC02LjEgNnptOS40LTYuOGMwLTEuMy0uMS0yLjktLjEtNC41LS40IDEuNC0uOSAyLjktMS4zIDQuM2wtMS4zIDQuM2gtMkw4LjUgNy45Yy0uNC0xLjMtLjctMi45LTEtNC4zLS4xIDEuNi0uMSAzLjItLjIgNC42TDcgMTIuNEg0LjhsLjctMTFoMy4zTDEwIDVjLjQgMS4yLjcgMi43IDEgMy45LjMtMS4yLjctMi42IDEtMy45bDEuMi0zLjdoMy4zbC42IDExaC0yLjRsLS4zLTQuMnoiLz4KPC9zdmc+Cg==);
  --jp-icon-move-down: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMTIuNDcxIDcuNTI4OTlDMTIuNzYzMiA3LjIzNjg0IDEyLjc2MzIgNi43NjMxNiAxMi40NzEgNi40NzEwMVY2LjQ3MTAxQzEyLjE3OSA2LjE3OTA1IDExLjcwNTcgNi4xNzg4NCAxMS40MTM1IDYuNDcwNTRMNy43NSAxMC4xMjc1VjEuNzVDNy43NSAxLjMzNTc5IDcuNDE0MjEgMSA3IDFWMUM2LjU4NTc5IDEgNi4yNSAxLjMzNTc5IDYuMjUgMS43NVYxMC4xMjc1TDIuNTk3MjYgNi40NjgyMkMyLjMwMzM4IDYuMTczODEgMS44MjY0MSA2LjE3MzU5IDEuNTMyMjYgNi40Njc3NFY2LjQ2Nzc0QzEuMjM4MyA2Ljc2MTcgMS4yMzgzIDcuMjM4MyAxLjUzMjI2IDcuNTMyMjZMNi4yOTI4OSAxMi4yOTI5QzYuNjgzNDIgMTIuNjgzNCA3LjMxNjU4IDEyLjY4MzQgNy43MDcxMSAxMi4yOTI5TDEyLjQ3MSA3LjUyODk5WiIgZmlsbD0iIzYxNjE2MSIvPgo8L3N2Zz4K);
  --jp-icon-move-up: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTQiIGhlaWdodD0iMTQiIHZpZXdCb3g9IjAgMCAxNCAxNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggY2xhc3M9ImpwLWljb24zIiBkPSJNMS41Mjg5OSA2LjQ3MTAxQzEuMjM2ODQgNi43NjMxNiAxLjIzNjg0IDcuMjM2ODQgMS41Mjg5OSA3LjUyODk5VjcuNTI4OTlDMS44MjA5NSA3LjgyMDk1IDIuMjk0MjYgNy44MjExNiAyLjU4NjQ5IDcuNTI5NDZMNi4yNSAzLjg3MjVWMTIuMjVDNi4yNSAxMi42NjQyIDYuNTg1NzkgMTMgNyAxM1YxM0M3LjQxNDIxIDEzIDcuNzUgMTIuNjY0MiA3Ljc1IDEyLjI1VjMuODcyNUwxMS40MDI3IDcuNTMxNzhDMTEuNjk2NiA3LjgyNjE5IDEyLjE3MzYgNy44MjY0MSAxMi40Njc3IDcuNTMyMjZWNy41MzIyNkMxMi43NjE3IDcuMjM4MyAxMi43NjE3IDYuNzYxNyAxMi40Njc3IDYuNDY3NzRMNy43MDcxMSAxLjcwNzExQzcuMzE2NTggMS4zMTY1OCA2LjY4MzQyIDEuMzE2NTggNi4yOTI4OSAxLjcwNzExTDEuNTI4OTkgNi40NzEwMVoiIGZpbGw9IiM2MTYxNjEiLz4KPC9zdmc+Cg==);
  --jp-icon-new-folder: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIwIDZoLThsLTItMkg0Yy0xLjExIDAtMS45OS44OS0xLjk5IDJMMiAxOGMwIDEuMTEuODkgMiAyIDJoMTZjMS4xMSAwIDItLjg5IDItMlY4YzAtMS4xMS0uODktMi0yLTJ6bS0xIDhoLTN2M2gtMnYtM2gtM3YtMmgzVjloMnYzaDN2MnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-not-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI1IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMTkgMTcuMTg0NCAyLjk2OTY4IDE0LjMwMzIgMS44NjA5NCAxMS40NDA5WiIvPgogICAgPHBhdGggY2xhc3M9ImpwLWljb24yIiBzdHJva2U9IiMzMzMzMzMiIHN0cm9rZS13aWR0aD0iMiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOS4zMTU5MiA5LjMyMDMxKSIgZD0iTTcuMzY4NDIgMEwwIDcuMzY0NzkiLz4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDkuMzE1OTIgMTYuNjgzNikgc2NhbGUoMSAtMSkiIGQ9Ik03LjM2ODQyIDBMMCA3LjM2NDc5Ii8+Cjwvc3ZnPgo=);
  --jp-icon-notebook: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtbm90ZWJvb2staWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiNFRjZDMDAiPgogICAgPHBhdGggZD0iTTE4LjcgMy4zdjE1LjRIMy4zVjMuM2gxNS40bTEuNS0xLjVIMS44djE4LjNoMTguM2wuMS0xOC4zeiIvPgogICAgPHBhdGggZD0iTTE2LjUgMTYuNWwtNS40LTQuMy01LjYgNC4zdi0xMWgxMXoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-numbering: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjIiIGhlaWdodD0iMjIiIHZpZXdCb3g9IjAgMCAyOCAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTQgMTlINlYxOS41SDVWMjAuNUg2VjIxSDRWMjJIN1YxOEg0VjE5Wk01IDEwSDZWNkg0VjdINVYxMFpNNCAxM0g1LjhMNCAxNS4xVjE2SDdWMTVINS4yTDcgMTIuOVYxMkg0VjEzWk05IDdWOUgyM1Y3SDlaTTkgMjFIMjNWMTlIOVYyMVpNOSAxNUgyM1YxM0g5VjE1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-offline-bolt: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyIDIuMDJjLTUuNTEgMC05Ljk4IDQuNDctOS45OCA5Ljk4czQuNDcgOS45OCA5Ljk4IDkuOTggOS45OC00LjQ3IDkuOTgtOS45OFMxNy41MSAyLjAyIDEyIDIuMDJ6TTExLjQ4IDIwdi02LjI2SDhMMTMgNHY2LjI2aDMuMzVMMTEuNDggMjB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-palette: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE4IDEzVjIwSDRWNkg5LjAyQzkuMDcgNS4yOSA5LjI0IDQuNjIgOS41IDRINEMyLjkgNCAyIDQuOSAyIDZWMjBDMiAyMS4xIDIuOSAyMiA0IDIySDE4QzE5LjEgMjIgMjAgMjEuMSAyMCAyMFYxNUwxOCAxM1pNMTkuMyA4Ljg5QzE5Ljc0IDguMTkgMjAgNy4zOCAyMCA2LjVDMjAgNC4wMSAxNy45OSAyIDE1LjUgMkMxMy4wMSAyIDExIDQuMDEgMTEgNi41QzExIDguOTkgMTMuMDEgMTEgMTUuNDkgMTFDMTYuMzcgMTEgMTcuMTkgMTAuNzQgMTcuODggMTAuM0wyMSAxMy40MkwyMi40MiAxMkwxOS4zIDguODlaTTE1LjUgOUMxNC4xMiA5IDEzIDcuODggMTMgNi41QzEzIDUuMTIgMTQuMTIgNCAxNS41IDRDMTYuODggNCAxOCA1LjEyIDE4IDYuNUMxOCA3Ljg4IDE2Ljg4IDkgMTUuNSA5WiIvPgogICAgPHBhdGggZmlsbC1ydWxlPSJldmVub2RkIiBjbGlwLXJ1bGU9ImV2ZW5vZGQiIGQ9Ik00IDZIOS4wMTg5NEM5LjAwNjM5IDYuMTY1MDIgOSA2LjMzMTc2IDkgNi41QzkgOC44MTU3NyAxMC4yMTEgMTAuODQ4NyAxMi4wMzQzIDEySDlWMTRIMTZWMTIuOTgxMUMxNi41NzAzIDEyLjkzNzcgMTcuMTIgMTIuODIwNyAxNy42Mzk2IDEyLjYzOTZMMTggMTNWMjBINFY2Wk04IDhINlYxMEg4VjhaTTYgMTJIOFYxNEg2VjEyWk04IDE2SDZWMThIOFYxNlpNOSAxNkgxNlYxOEg5VjE2WiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-paste: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE5IDJoLTQuMThDMTQuNC44NCAxMy4zIDAgMTIgMGMtMS4zIDAtMi40Ljg0LTIuODIgMkg1Yy0xLjEgMC0yIC45LTIgMnYxNmMwIDEuMS45IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjRjMC0xLjEtLjktMi0yLTJ6bS03IDBjLjU1IDAgMSAuNDUgMSAxcy0uNDUgMS0xIDEtMS0uNDUtMS0xIC40NS0xIDEtMXptNyAxOEg1VjRoMnYzaDEwVjRoMnYxNnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-pdf: url(data:image/svg+xml;base64,PHN2ZwogICB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyMiAyMiIgd2lkdGg9IjE2Ij4KICAgIDxwYXRoIHRyYW5zZm9ybT0icm90YXRlKDQ1KSIgY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI0ZGMkEyQSIKICAgICAgIGQ9Im0gMjIuMzQ0MzY5LC0zLjAxNjM2NDIgaCA1LjYzODYwNCB2IDEuNTc5MjQzMyBoIC0zLjU0OTIyNyB2IDEuNTA4NjkyOTkgaCAzLjMzNzU3NiBWIDEuNjUwODE1NCBoIC0zLjMzNzU3NiB2IDMuNDM1MjYxMyBoIC0yLjA4OTM3NyB6IG0gLTcuMTM2NDQ0LDEuNTc5MjQzMyB2IDQuOTQzOTU0MyBoIDAuNzQ4OTIgcSAxLjI4MDc2MSwwIDEuOTUzNzAzLC0wLjYzNDk1MzUgMC42NzgzNjksLTAuNjM0OTUzNSAwLjY3ODM2OSwtMS44NDUxNjQxIDAsLTEuMjA0NzgzNTUgLTAuNjcyOTQyLC0xLjgzNDMxMDExIC0wLjY3Mjk0MiwtMC42Mjk1MjY1OSAtMS45NTkxMywtMC42Mjk1MjY1OSB6IG0gLTIuMDg5Mzc3LC0xLjU3OTI0MzMgaCAyLjIwMzM0MyBxIDEuODQ1MTY0LDAgMi43NDYwMzksMC4yNjU5MjA3IDAuOTA2MzAxLDAuMjYwNDkzNyAxLjU1MjEwOCwwLjg5MDAyMDMgMC41Njk4MywwLjU0ODEyMjMgMC44NDY2MDUsMS4yNjQ0ODAwNiAwLjI3Njc3NCwwLjcxNjM1NzgxIDAuMjc2Nzc0LDEuNjIyNjU4OTQgMCwwLjkxNzE1NTEgLTAuMjc2Nzc0LDEuNjM4OTM5OSAtMC4yNzY3NzUsMC43MTYzNTc4IC0wLjg0NjYwNSwxLjI2NDQ4IC0wLjY1MTIzNCwwLjYyOTUyNjYgLTEuNTYyOTYyLDAuODk1NDQ3MyAtMC45MTE3MjgsMC4yNjA0OTM3IC0yLjczNTE4NSwwLjI2MDQ5MzcgaCAtMi4yMDMzNDMgeiBtIC04LjE0NTg1NjUsMCBoIDMuNDY3ODIzIHEgMS41NDY2ODE2LDAgMi4zNzE1Nzg1LDAuNjg5MjIzIDAuODMwMzI0LDAuNjgzNzk2MSAwLjgzMDMyNCwxLjk1MzcwMzE0IDAsMS4yNzUzMzM5NyAtMC44MzAzMjQsMS45NjQ1NTcwNiBRIDkuOTg3MTk2MSwyLjI3NDkxNSA4LjQ0MDUxNDUsMi4yNzQ5MTUgSCA3LjA2MjA2ODQgViA1LjA4NjA3NjcgSCA0Ljk3MjY5MTUgWiBtIDIuMDg5Mzc2OSwxLjUxNDExOTkgdiAyLjI2MzAzOTQzIGggMS4xNTU5NDEgcSAwLjYwNzgxODgsMCAwLjkzODg2MjksLTAuMjkzMDU1NDcgMC4zMzEwNDQxLC0wLjI5ODQ4MjQxIDAuMzMxMDQ0MSwtMC44NDExNzc3MiAwLC0wLjU0MjY5NTMxIC0wLjMzMTA0NDEsLTAuODM1NzUwNzQgLTAuMzMxMDQ0MSwtMC4yOTMwNTU1IC0wLjkzODg2MjksLTAuMjkzMDU1NSB6IgovPgo8L3N2Zz4K);
  --jp-icon-python: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iLTEwIC0xMCAxMzEuMTYxMzYxNjk0MzM1OTQgMTMyLjM4ODk5OTkzODk2NDg0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMzA2OTk4IiBkPSJNIDU0LjkxODc4NSw5LjE5Mjc0MjFlLTQgQyA1MC4zMzUxMzIsMC4wMjIyMTcyNyA0NS45NTc4NDYsMC40MTMxMzY5NyA0Mi4xMDYyODUsMS4wOTQ2NjkzIDMwLjc2MDA2OSwzLjA5OTE3MzEgMjguNzAwMDM2LDcuMjk0NzcxNCAyOC43MDAwMzUsMTUuMDMyMTY5IHYgMTAuMjE4NzUgaCAyNi44MTI1IHYgMy40MDYyNSBoIC0yNi44MTI1IC0xMC4wNjI1IGMgLTcuNzkyNDU5LDAgLTE0LjYxNTc1ODgsNC42ODM3MTcgLTE2Ljc0OTk5OTgsMTMuNTkzNzUgLTIuNDYxODE5OTgsMTAuMjEyOTY2IC0yLjU3MTAxNTA4LDE2LjU4NjAyMyAwLDI3LjI1IDEuOTA1OTI4Myw3LjkzNzg1MiA2LjQ1NzU0MzIsMTMuNTkzNzQ4IDE0LjI0OTk5OTgsMTMuNTkzNzUgaCA5LjIxODc1IHYgLTEyLjI1IGMgMCwtOC44NDk5MDIgNy42NTcxNDQsLTE2LjY1NjI0OCAxNi43NSwtMTYuNjU2MjUgaCAyNi43ODEyNSBjIDcuNDU0OTUxLDAgMTMuNDA2MjUzLC02LjEzODE2NCAxMy40MDYyNSwtMTMuNjI1IHYgLTI1LjUzMTI1IGMgMCwtNy4yNjYzMzg2IC02LjEyOTk4LC0xMi43MjQ3NzcxIC0xMy40MDYyNSwtMTMuOTM3NDk5NyBDIDY0LjI4MTU0OCwwLjMyNzk0Mzk3IDU5LjUwMjQzOCwtMC4wMjAzNzkwMyA1NC45MTg3ODUsOS4xOTI3NDIxZS00IFogbSAtMTQuNSw4LjIxODc1MDEyNTc5IGMgMi43Njk1NDcsMCA1LjAzMTI1LDIuMjk4NjQ1NiA1LjAzMTI1LDUuMTI0OTk5NiAtMmUtNiwyLjgxNjMzNiAtMi4yNjE3MDMsNS4wOTM3NSAtNS4wMzEyNSw1LjA5Mzc1IC0yLjc3OTQ3NiwtMWUtNiAtNS4wMzEyNSwtMi4yNzc0MTUgLTUuMDMxMjUsLTUuMDkzNzUgLTEwZS03LC0yLjgyNjM1MyAyLjI1MTc3NCwtNS4xMjQ5OTk2IDUuMDMxMjUsLTUuMTI0OTk5NiB6Ii8+CiAgPHBhdGggY2xhc3M9ImpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iI2ZmZDQzYiIgZD0ibSA4NS42Mzc1MzUsMjguNjU3MTY5IHYgMTEuOTA2MjUgYyAwLDkuMjMwNzU1IC03LjgyNTg5NSwxNi45OTk5OTkgLTE2Ljc1LDE3IGggLTI2Ljc4MTI1IGMgLTcuMzM1ODMzLDAgLTEzLjQwNjI0OSw2LjI3ODQ4MyAtMTMuNDA2MjUsMTMuNjI1IHYgMjUuNTMxMjQ3IGMgMCw3LjI2NjM0NCA2LjMxODU4OCwxMS41NDAzMjQgMTMuNDA2MjUsMTMuNjI1MDA0IDguNDg3MzMxLDIuNDk1NjEgMTYuNjI2MjM3LDIuOTQ2NjMgMjYuNzgxMjUsMCA2Ljc1MDE1NSwtMS45NTQzOSAxMy40MDYyNTMsLTUuODg3NjEgMTMuNDA2MjUsLTEzLjYyNTAwNCBWIDg2LjUwMDkxOSBoIC0yNi43ODEyNSB2IC0zLjQwNjI1IGggMjYuNzgxMjUgMTMuNDA2MjU0IGMgNy43OTI0NjEsMCAxMC42OTYyNTEsLTUuNDM1NDA4IDEzLjQwNjI0MSwtMTMuNTkzNzUgMi43OTkzMywtOC4zOTg4ODYgMi42ODAyMiwtMTYuNDc1Nzc2IDAsLTI3LjI1IC0xLjkyNTc4LC03Ljc1NzQ0MSAtNS42MDM4NywtMTMuNTkzNzUgLTEzLjQwNjI0MSwtMTMuNTkzNzUgeiBtIC0xNS4wNjI1LDY0LjY1NjI1IGMgMi43Nzk0NzgsM2UtNiA1LjAzMTI1LDIuMjc3NDE3IDUuMDMxMjUsNS4wOTM3NDcgLTJlLTYsMi44MjYzNTQgLTIuMjUxNzc1LDUuMTI1MDA0IC01LjAzMTI1LDUuMTI1MDA0IC0yLjc2OTU1LDAgLTUuMDMxMjUsLTIuMjk4NjUgLTUuMDMxMjUsLTUuMTI1MDA0IDJlLTYsLTIuODE2MzMgMi4yNjE2OTcsLTUuMDkzNzQ3IDUuMDMxMjUsLTUuMDkzNzQ3IHoiLz4KPC9zdmc+Cg==);
  --jp-icon-r-kernel: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjE5NkYzIiBkPSJNNC40IDIuNWMxLjItLjEgMi45LS4zIDQuOS0uMyAyLjUgMCA0LjEuNCA1LjIgMS4zIDEgLjcgMS41IDEuOSAxLjUgMy41IDAgMi0xLjQgMy41LTIuOSA0LjEgMS4yLjQgMS43IDEuNiAyLjIgMyAuNiAxLjkgMSAzLjkgMS4zIDQuNmgtMy44Yy0uMy0uNC0uOC0xLjctMS4yLTMuN3MtMS4yLTIuNi0yLjYtMi42aC0uOXY2LjRINC40VjIuNXptMy43IDYuOWgxLjRjMS45IDAgMi45LS45IDIuOS0yLjNzLTEtMi4zLTIuOC0yLjNjLS43IDAtMS4zIDAtMS42LjJ2NC41aC4xdi0uMXoiLz4KPC9zdmc+Cg==);
  --jp-icon-react: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMTUwIDE1MCA1NDEuOSAyOTUuMyI+CiAgPGcgY2xhc3M9ImpwLWljb24tYnJhbmQyIGpwLWljb24tc2VsZWN0YWJsZSIgZmlsbD0iIzYxREFGQiI+CiAgICA8cGF0aCBkPSJNNjY2LjMgMjk2LjVjMC0zMi41LTQwLjctNjMuMy0xMDMuMS04Mi40IDE0LjQtNjMuNiA4LTExNC4yLTIwLjItMTMwLjQtNi41LTMuOC0xNC4xLTUuNi0yMi40LTUuNnYyMi4zYzQuNiAwIDguMy45IDExLjQgMi42IDEzLjYgNy44IDE5LjUgMzcuNSAxNC45IDc1LjctMS4xIDkuNC0yLjkgMTkuMy01LjEgMjkuNC0xOS42LTQuOC00MS04LjUtNjMuNS0xMC45LTEzLjUtMTguNS0yNy41LTM1LjMtNDEuNi01MCAzMi42LTMwLjMgNjMuMi00Ni45IDg0LTQ2LjlWNzhjLTI3LjUgMC02My41IDE5LjYtOTkuOSA1My42LTM2LjQtMzMuOC03Mi40LTUzLjItOTkuOS01My4ydjIyLjNjMjAuNyAwIDUxLjQgMTYuNSA4NCA0Ni42LTE0IDE0LjctMjggMzEuNC00MS4zIDQ5LjktMjIuNiAyLjQtNDQgNi4xLTYzLjYgMTEtMi4zLTEwLTQtMTkuNy01LjItMjktNC43LTM4LjIgMS4xLTY3LjkgMTQuNi03NS44IDMtMS44IDYuOS0yLjYgMTEuNS0yLjZWNzguNWMtOC40IDAtMTYgMS44LTIyLjYgNS42LTI4LjEgMTYuMi0zNC40IDY2LjctMTkuOSAxMzAuMS02Mi4yIDE5LjItMTAyLjcgNDkuOS0xMDIuNyA4Mi4zIDAgMzIuNSA0MC43IDYzLjMgMTAzLjEgODIuNC0xNC40IDYzLjYtOCAxMTQuMiAyMC4yIDEzMC40IDYuNSAzLjggMTQuMSA1LjYgMjIuNSA1LjYgMjcuNSAwIDYzLjUtMTkuNiA5OS45LTUzLjYgMzYuNCAzMy44IDcyLjQgNTMuMiA5OS45IDUzLjIgOC40IDAgMTYtMS44IDIyLjYtNS42IDI4LjEtMTYuMiAzNC40LTY2LjcgMTkuOS0xMzAuMSA2Mi0xOS4xIDEwMi41LTQ5LjkgMTAyLjUtODIuM3ptLTEzMC4yLTY2LjdjLTMuNyAxMi45LTguMyAyNi4yLTEzLjUgMzkuNS00LjEtOC04LjQtMTYtMTMuMS0yNC00LjYtOC05LjUtMTUuOC0xNC40LTIzLjQgMTQuMiAyLjEgMjcuOSA0LjcgNDEgNy45em0tNDUuOCAxMDYuNWMtNy44IDEzLjUtMTUuOCAyNi4zLTI0LjEgMzguMi0xNC45IDEuMy0zMCAyLTQ1LjIgMi0xNS4xIDAtMzAuMi0uNy00NS0xLjktOC4zLTExLjktMTYuNC0yNC42LTI0LjItMzgtNy42LTEzLjEtMTQuNS0yNi40LTIwLjgtMzkuOCA2LjItMTMuNCAxMy4yLTI2LjggMjAuNy0zOS45IDcuOC0xMy41IDE1LjgtMjYuMyAyNC4xLTM4LjIgMTQuOS0xLjMgMzAtMiA0NS4yLTIgMTUuMSAwIDMwLjIuNyA0NSAxLjkgOC4zIDExLjkgMTYuNCAyNC42IDI0LjIgMzggNy42IDEzLjEgMTQuNSAyNi40IDIwLjggMzkuOC02LjMgMTMuNC0xMy4yIDI2LjgtMjAuNyAzOS45em0zMi4zLTEzYzUuNCAxMy40IDEwIDI2LjggMTMuOCAzOS44LTEzLjEgMy4yLTI2LjkgNS45LTQxLjIgOCA0LjktNy43IDkuOC0xNS42IDE0LjQtMjMuNyA0LjYtOCA4LjktMTYuMSAxMy0yNC4xek00MjEuMiA0MzBjLTkuMy05LjYtMTguNi0yMC4zLTI3LjgtMzIgOSAuNCAxOC4yLjcgMjcuNS43IDkuNCAwIDE4LjctLjIgMjcuOC0uNy05IDExLjctMTguMyAyMi40LTI3LjUgMzJ6bS03NC40LTU4LjljLTE0LjItMi4xLTI3LjktNC43LTQxLTcuOSAzLjctMTIuOSA4LjMtMjYuMiAxMy41LTM5LjUgNC4xIDggOC40IDE2IDEzLjEgMjQgNC43IDggOS41IDE1LjggMTQuNCAyMy40ek00MjAuNyAxNjNjOS4zIDkuNiAxOC42IDIwLjMgMjcuOCAzMi05LS40LTE4LjItLjctMjcuNS0uNy05LjQgMC0xOC43LjItMjcuOC43IDktMTEuNyAxOC4zLTIyLjQgMjcuNS0zMnptLTc0IDU4LjljLTQuOSA3LjctOS44IDE1LjYtMTQuNCAyMy43LTQuNiA4LTguOSAxNi0xMyAyNC01LjQtMTMuNC0xMC0yNi44LTEzLjgtMzkuOCAxMy4xLTMuMSAyNi45LTUuOCA0MS4yLTcuOXptLTkwLjUgMTI1LjJjLTM1LjQtMTUuMS01OC4zLTM0LjktNTguMy01MC42IDAtMTUuNyAyMi45LTM1LjYgNTguMy01MC42IDguNi0zLjcgMTgtNyAyNy43LTEwLjEgNS43IDE5LjYgMTMuMiA0MCAyMi41IDYwLjktOS4yIDIwLjgtMTYuNiA0MS4xLTIyLjIgNjAuNi05LjktMy4xLTE5LjMtNi41LTI4LTEwLjJ6TTMxMCA0OTBjLTEzLjYtNy44LTE5LjUtMzcuNS0xNC45LTc1LjcgMS4xLTkuNCAyLjktMTkuMyA1LjEtMjkuNCAxOS42IDQuOCA0MSA4LjUgNjMuNSAxMC45IDEzLjUgMTguNSAyNy41IDM1LjMgNDEuNiA1MC0zMi42IDMwLjMtNjMuMiA0Ni45LTg0IDQ2LjktNC41LS4xLTguMy0xLTExLjMtMi43em0yMzcuMi03Ni4yYzQuNyAzOC4yLTEuMSA2Ny45LTE0LjYgNzUuOC0zIDEuOC02LjkgMi42LTExLjUgMi42LTIwLjcgMC01MS40LTE2LjUtODQtNDYuNiAxNC0xNC43IDI4LTMxLjQgNDEuMy00OS45IDIyLjYtMi40IDQ0LTYuMSA2My42LTExIDIuMyAxMC4xIDQuMSAxOS44IDUuMiAyOS4xem0zOC41LTY2LjdjLTguNiAzLjctMTggNy0yNy43IDEwLjEtNS43LTE5LjYtMTMuMi00MC0yMi41LTYwLjkgOS4yLTIwLjggMTYuNi00MS4xIDIyLjItNjAuNiA5LjkgMy4xIDE5LjMgNi41IDI4LjEgMTAuMiAzNS40IDE1LjEgNTguMyAzNC45IDU4LjMgNTAuNi0uMSAxNS43LTIzIDM1LjYtNTguNCA1MC42ek0zMjAuOCA3OC40eiIvPgogICAgPGNpcmNsZSBjeD0iNDIwLjkiIGN5PSIyOTYuNSIgcj0iNDUuNyIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-redo: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjE2Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgICA8cGF0aCBkPSJNMCAwaDI0djI0SDB6IiBmaWxsPSJub25lIi8+PHBhdGggZD0iTTE4LjQgMTAuNkMxNi41NSA4Ljk5IDE0LjE1IDggMTEuNSA4Yy00LjY1IDAtOC41OCAzLjAzLTkuOTYgNy4yMkwzLjkgMTZjMS4wNS0zLjE5IDQuMDUtNS41IDcuNi01LjUgMS45NSAwIDMuNzMuNzIgNS4xMiAxLjg4TDEzIDE2aDlWN2wtMy42IDMuNnoiLz4KICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-refresh: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTkgMTMuNWMtMi40OSAwLTQuNS0yLjAxLTQuNS00LjVTNi41MSA0LjUgOSA0LjVjMS4yNCAwIDIuMzYuNTIgMy4xNyAxLjMzTDEwIDhoNVYzbC0xLjc2IDEuNzZDMTIuMTUgMy42OCAxMC42NiAzIDkgMyA1LjY5IDMgMy4wMSA1LjY5IDMuMDEgOVM1LjY5IDE1IDkgMTVjMi45NyAwIDUuNDMtMi4xNiA1LjktNWgtMS41MmMtLjQ2IDItMi4yNCAzLjUtNC4zOCAzLjV6Ii8+CiAgICA8L2c+Cjwvc3ZnPgo=);
  --jp-icon-regex: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KICA8ZyBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiM0MTQxNDEiPgogICAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiAgPC9nPgoKICA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiBmaWxsPSIjRkZGIj4KICAgIDxjaXJjbGUgY2xhc3M9InN0MiIgY3g9IjUuNSIgY3k9IjE0LjUiIHI9IjEuNSIvPgogICAgPHJlY3QgeD0iMTIiIHk9IjQiIGNsYXNzPSJzdDIiIHdpZHRoPSIxIiBoZWlnaHQ9IjgiLz4KICAgIDxyZWN0IHg9IjguNSIgeT0iNy41IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjg2NiAtMC41IDAuNSAwLjg2NiAtMi4zMjU1IDcuMzIxOSkiIGNsYXNzPSJzdDIiIHdpZHRoPSI4IiBoZWlnaHQ9IjEiLz4KICAgIDxyZWN0IHg9IjEyIiB5PSI0IiB0cmFuc2Zvcm09Im1hdHJpeCgwLjUgLTAuODY2IDAuODY2IDAuNSAtMC42Nzc5IDE0LjgyNTIpIiBjbGFzcz0ic3QyIiB3aWR0aD0iMSIgaGVpZ2h0PSI4Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-run: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTggNXYxNGwxMS03eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-running: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDUxMiA1MTIiPgogIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICA8cGF0aCBkPSJNMjU2IDhDMTE5IDggOCAxMTkgOCAyNTZzMTExIDI0OCAyNDggMjQ4IDI0OC0xMTEgMjQ4LTI0OFMzOTMgOCAyNTYgOHptOTYgMzI4YzAgOC44LTcuMiAxNi0xNiAxNkgxNzZjLTguOCAwLTE2LTcuMi0xNi0xNlYxNzZjMC04LjggNy4yLTE2IDE2LTE2aDE2MGM4LjggMCAxNiA3LjIgMTYgMTZ2MTYweiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-save: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTE3IDNINWMtMS4xMSAwLTIgLjktMiAydjE0YzAgMS4xLjg5IDIgMiAyaDE0YzEuMSAwIDItLjkgMi0yVjdsLTQtNHptLTUgMTZjLTEuNjYgMC0zLTEuMzQtMy0zczEuMzQtMyAzLTMgMyAxLjM0IDMgMy0xLjM0IDMtMyAzem0zLTEwSDVWNWgxMHY0eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-search: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMTggMTgiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjEsMTAuOWgtMC43bC0wLjItMC4yYzAuOC0wLjksMS4zLTIuMiwxLjMtMy41YzAtMy0yLjQtNS40LTUuNC01LjRTMS44LDQuMiwxLjgsNy4xczIuNCw1LjQsNS40LDUuNCBjMS4zLDAsMi41LTAuNSwzLjUtMS4zbDAuMiwwLjJ2MC43bDQuMSw0LjFsMS4yLTEuMkwxMi4xLDEwLjl6IE03LjEsMTAuOWMtMi4xLDAtMy43LTEuNy0zLjctMy43czEuNy0zLjcsMy43LTMuN3MzLjcsMS43LDMuNywzLjcgUzkuMiwxMC45LDcuMSwxMC45eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-settings: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIiBkPSJNMTkuNDMgMTIuOThjLjA0LS4zMi4wNy0uNjQuMDctLjk4cy0uMDMtLjY2LS4wNy0uOThsMi4xMS0xLjY1Yy4xOS0uMTUuMjQtLjQyLjEyLS42NGwtMi0zLjQ2Yy0uMTItLjIyLS4zOS0uMy0uNjEtLjIybC0yLjQ5IDFjLS41Mi0uNC0xLjA4LS43My0xLjY5LS45OGwtLjM4LTIuNjVBLjQ4OC40ODggMCAwMDE0IDJoLTRjLS4yNSAwLS40Ni4xOC0uNDkuNDJsLS4zOCAyLjY1Yy0uNjEuMjUtMS4xNy41OS0xLjY5Ljk4bC0yLjQ5LTFjLS4yMy0uMDktLjQ5IDAtLjYxLjIybC0yIDMuNDZjLS4xMy4yMi0uMDcuNDkuMTIuNjRsMi4xMSAxLjY1Yy0uMDQuMzItLjA3LjY1LS4wNy45OHMuMDMuNjYuMDcuOThsLTIuMTEgMS42NWMtLjE5LjE1LS4yNC40Mi0uMTIuNjRsMiAzLjQ2Yy4xMi4yMi4zOS4zLjYxLjIybDIuNDktMWMuNTIuNCAxLjA4LjczIDEuNjkuOThsLjM4IDIuNjVjLjAzLjI0LjI0LjQyLjQ5LjQyaDRjLjI1IDAgLjQ2LS4xOC40OS0uNDJsLjM4LTIuNjVjLjYxLS4yNSAxLjE3LS41OSAxLjY5LS45OGwyLjQ5IDFjLjIzLjA5LjQ5IDAgLjYxLS4yMmwyLTMuNDZjLjEyLS4yMi4wNy0uNDktLjEyLS42NGwtMi4xMS0xLjY1ek0xMiAxNS41Yy0xLjkzIDAtMy41LTEuNTctMy41LTMuNXMxLjU3LTMuNSAzLjUtMy41IDMuNSAxLjU3IDMuNSAzLjUtMS41NyAzLjUtMy41IDMuNXoiLz4KPC9zdmc+Cg==);
  --jp-icon-share: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTSAxOCAyIEMgMTYuMzU0OTkgMiAxNSAzLjM1NDk5MDQgMTUgNSBDIDE1IDUuMTkwOTUyOSAxNS4wMjE3OTEgNS4zNzcxMjI0IDE1LjA1NjY0MSA1LjU1ODU5MzggTCA3LjkyMTg3NSA5LjcyMDcwMzEgQyA3LjM5ODUzOTkgOS4yNzc4NTM5IDYuNzMyMDc3MSA5IDYgOSBDIDQuMzU0OTkwNCA5IDMgMTAuMzU0OTkgMyAxMiBDIDMgMTMuNjQ1MDEgNC4zNTQ5OTA0IDE1IDYgMTUgQyA2LjczMjA3NzEgMTUgNy4zOTg1Mzk5IDE0LjcyMjE0NiA3LjkyMTg3NSAxNC4yNzkyOTcgTCAxNS4wNTY2NDEgMTguNDM5NDUzIEMgMTUuMDIxNTU1IDE4LjYyMTUxNCAxNSAxOC44MDgzODYgMTUgMTkgQyAxNSAyMC42NDUwMSAxNi4zNTQ5OSAyMiAxOCAyMiBDIDE5LjY0NTAxIDIyIDIxIDIwLjY0NTAxIDIxIDE5IEMgMjEgMTcuMzU0OTkgMTkuNjQ1MDEgMTYgMTggMTYgQyAxNy4yNjc0OCAxNiAxNi42MDE1OTMgMTYuMjc5MzI4IDE2LjA3ODEyNSAxNi43MjI2NTYgTCA4Ljk0MzM1OTQgMTIuNTU4NTk0IEMgOC45NzgyMDk1IDEyLjM3NzEyMiA5IDEyLjE5MDk1MyA5IDEyIEMgOSAxMS44MDkwNDcgOC45NzgyMDk1IDExLjYyMjg3OCA4Ljk0MzM1OTQgMTEuNDQxNDA2IEwgMTYuMDc4MTI1IDcuMjc5Mjk2OSBDIDE2LjYwMTQ2IDcuNzIyMTQ2MSAxNy4yNjc5MjMgOCAxOCA4IEMgMTkuNjQ1MDEgOCAyMSA2LjY0NTAwOTYgMjEgNSBDIDIxIDMuMzU0OTkwNCAxOS42NDUwMSAyIDE4IDIgeiBNIDE4IDQgQyAxOC41NjQxMjkgNCAxOSA0LjQzNTg3MDYgMTkgNSBDIDE5IDUuNTY0MTI5NCAxOC41NjQxMjkgNiAxOCA2IEMgMTcuNDM1ODcxIDYgMTcgNS41NjQxMjk0IDE3IDUgQyAxNyA0LjQzNTg3MDYgMTcuNDM1ODcxIDQgMTggNCB6IE0gNiAxMSBDIDYuNTY0MTI5NCAxMSA3IDExLjQzNTg3MSA3IDEyIEMgNyAxMi41NjQxMjkgNi41NjQxMjk0IDEzIDYgMTMgQyA1LjQzNTg3MDYgMTMgNSAxMi41NjQxMjkgNSAxMiBDIDUgMTEuNDM1ODcxIDUuNDM1ODcwNiAxMSA2IDExIHogTSAxOCAxOCBDIDE4LjU2NDEyOSAxOCAxOSAxOC40MzU4NzEgMTkgMTkgQyAxOSAxOS41NjQxMjkgMTguNTY0MTI5IDIwIDE4IDIwIEMgMTcuNDM1ODcxIDIwIDE3IDE5LjU2NDEyOSAxNyAxOSBDIDE3IDE4LjQzNTg3MSAxNy40MzU4NzEgMTggMTggMTggeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-spreadsheet: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8cGF0aCBjbGFzcz0ianAtaWNvbi1jb250cmFzdDEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNENBRjUwIiBkPSJNMi4yIDIuMnYxNy42aDE3LjZWMi4ySDIuMnptMTUuNCA3LjdoLTUuNVY0LjRoNS41djUuNXpNOS45IDQuNHY1LjVINC40VjQuNGg1LjV6bS01LjUgNy43aDUuNXY1LjVINC40di01LjV6bTcuNyA1LjV2LTUuNWg1LjV2NS41aC01LjV6Ii8+Cjwvc3ZnPgo=);
  --jp-icon-stop: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik02IDZoMTJ2MTJINnoiLz4KICAgIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tab: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTIxIDNIM2MtMS4xIDAtMiAuOS0yIDJ2MTRjMCAxLjEuOSAyIDIgMmgxOGMxLjEgMCAyLS45IDItMlY1YzAtMS4xLS45LTItMi0yem0wIDE2SDNWNWgxMHY0aDh2MTB6Ii8+CiAgPC9nPgo8L3N2Zz4K);
  --jp-icon-table-rows: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMSw4SDNWNGgxOFY4eiBNMjEsMTBIM3Y0aDE4VjEweiBNMjEsMTZIM3Y0aDE4VjE2eiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-tag: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjgiIGhlaWdodD0iMjgiIHZpZXdCb3g9IjAgMCA0MyAyOCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KCTxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CgkJPHBhdGggZD0iTTI4LjgzMzIgMTIuMzM0TDMyLjk5OTggMTYuNTAwN0wzNy4xNjY1IDEyLjMzNEgyOC44MzMyWiIvPgoJCTxwYXRoIGQ9Ik0xNi4yMDk1IDIxLjYxMDRDMTUuNjg3MyAyMi4xMjk5IDE0Ljg0NDMgMjIuMTI5OSAxNC4zMjQ4IDIxLjYxMDRMNi45ODI5IDE0LjcyNDVDNi41NzI0IDE0LjMzOTQgNi4wODMxMyAxMy42MDk4IDYuMDQ3ODYgMTMuMDQ4MkM1Ljk1MzQ3IDExLjUyODggNi4wMjAwMiA4LjYxOTQ0IDYuMDY2MjEgNy4wNzY5NUM2LjA4MjgxIDYuNTE0NzcgNi41NTU0OCA2LjA0MzQ3IDcuMTE4MDQgNi4wMzA1NUM5LjA4ODYzIDUuOTg0NzMgMTMuMjYzOCA1LjkzNTc5IDEzLjY1MTggNi4zMjQyNUwyMS43MzY5IDEzLjYzOUMyMi4yNTYgMTQuMTU4NSAyMS43ODUxIDE1LjQ3MjQgMjEuMjYyIDE1Ljk5NDZMMTYuMjA5NSAyMS42MTA0Wk05Ljc3NTg1IDguMjY1QzkuMzM1NTEgNy44MjU2NiA4LjYyMzUxIDcuODI1NjYgOC4xODI4IDguMjY1QzcuNzQzNDYgOC43MDU3MSA3Ljc0MzQ2IDkuNDE3MzMgOC4xODI4IDkuODU2NjdDOC42MjM4MiAxMC4yOTY0IDkuMzM1ODIgMTAuMjk2NCA5Ljc3NTg1IDkuODU2NjdDMTAuMjE1NiA5LjQxNzMzIDEwLjIxNTYgOC43MDUzMyA5Ljc3NTg1IDguMjY1WiIvPgoJPC9nPgo8L3N2Zz4K);
  --jp-icon-terminal: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0IiA+CiAgICA8cmVjdCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1iYWNrZ3JvdW5kLWNvbG9yIGpwLWljb24tc2VsZWN0YWJsZSIgd2lkdGg9IjIwIiBoZWlnaHQ9IjIwIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgyIDIpIiBmaWxsPSIjMzMzMzMzIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtdGVybWluYWwtaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUtaW52ZXJzZSIgZD0iTTUuMDU2NjQgOC43NjE3MkM1LjA1NjY0IDguNTk3NjYgNS4wMzEyNSA4LjQ1MzEyIDQuOTgwNDcgOC4zMjgxMkM0LjkzMzU5IDguMTk5MjIgNC44NTU0NyA4LjA4MjAzIDQuNzQ2MDkgNy45NzY1NkM0LjY0MDYyIDcuODcxMDkgNC41IDcuNzc1MzkgNC4zMjQyMiA3LjY4OTQ1QzQuMTUyMzQgNy41OTk2MSAzLjk0MzM2IDcuNTExNzIgMy42OTcyNyA3LjQyNTc4QzMuMzAyNzMgNy4yODUxNiAyLjk0MzM2IDcuMTM2NzIgMi42MTkxNCA2Ljk4MDQ3QzIuMjk0OTIgNi44MjQyMiAyLjAxNzU4IDYuNjQyNTggMS43ODcxMSA2LjQzNTU1QzEuNTYwNTUgNi4yMjg1MiAxLjM4NDc3IDUuOTg4MjggMS4yNTk3NyA1LjcxNDg0QzEuMTM0NzcgNS40Mzc1IDEuMDcyMjcgNS4xMDkzOCAxLjA3MjI3IDQuNzMwNDdDMS4wNzIyNyA0LjM5ODQ0IDEuMTI4OTEgNC4wOTU3IDEuMjQyMTkgMy44MjIyN0MxLjM1NTQ3IDMuNTQ0OTIgMS41MTU2MiAzLjMwNDY5IDEuNzIyNjYgMy4xMDE1NkMxLjkyOTY5IDIuODk4NDQgMi4xNzk2OSAyLjczNDM3IDIuNDcyNjYgMi42MDkzOEMyLjc2NTYyIDIuNDg0MzggMy4wOTE4IDIuNDA0MyAzLjQ1MTE3IDIuMzY5MTRWMS4xMDkzOEg0LjM4ODY3VjIuMzgwODZDNC43NDAyMyAyLjQyNzczIDUuMDU2NjQgMi41MjM0NCA1LjMzNzg5IDIuNjY3OTdDNS42MTkxNCAyLjgxMjUgNS44NTc0MiAzLjAwMTk1IDYuMDUyNzMgMy4yMzYzM0M2LjI1MTk1IDMuNDY2OCA2LjQwNDMgMy43NDAyMyA2LjUwOTc3IDQuMDU2NjRDNi42MTkxNCA0LjM2OTE0IDYuNjczODMgNC43MjA3IDYuNjczODMgNS4xMTEzM0g1LjA0NDkyQzUuMDQ0OTIgNC42Mzg2NyA0LjkzNzUgNC4yODEyNSA0LjcyMjY2IDQuMDM5MDZDNC41MDc4MSAzLjc5Mjk3IDQuMjE2OCAzLjY2OTkyIDMuODQ5NjEgMy42Njk5MkMzLjY1MDM5IDMuNjY5OTIgMy40NzY1NiAzLjY5NzI3IDMuMzI4MTIgMy43NTE5NUMzLjE4MzU5IDMuODAyNzMgMy4wNjQ0NSAzLjg3Njk1IDIuOTcwNyAzLjk3NDYxQzIuODc2OTUgNC4wNjgzNiAyLjgwNjY0IDQuMTc5NjkgMi43NTk3NyA0LjMwODU5QzIuNzE2OCA0LjQzNzUgMi42OTUzMSA0LjU3ODEyIDIuNjk1MzEgNC43MzA0N0MyLjY5NTMxIDQuODgyODEgMi43MTY4IDUuMDE5NTMgMi43NTk3NyA1LjE0MDYyQzIuODA2NjQgNS4yNTc4MSAyLjg4MjgxIDUuMzY3MTkgMi45ODgyOCA1LjQ2ODc1QzMuMDk3NjYgNS41NzAzMSAzLjI0MDIzIDUuNjY3OTcgMy40MTYwMiA1Ljc2MTcyQzMuNTkxOCA1Ljg1MTU2IDMuODEwNTUgNS45NDMzNiA0LjA3MjI3IDYuMDM3MTFDNC40NjY4IDYuMTg1NTUgNC44MjQyMiA2LjMzOTg0IDUuMTQ0NTMgNi41QzUuNDY0ODQgNi42NTYyNSA1LjczODI4IDYuODM5ODQgNS45NjQ4NCA3LjA1MDc4QzYuMTk1MzEgNy4yNTc4MSA2LjM3MTA5IDcuNSA2LjQ5MjE5IDcuNzc3MzRDNi42MTcxOSA4LjA1MDc4IDYuNjc5NjkgOC4zNzUgNi42Nzk2OSA4Ljc1QzYuNjc5NjkgOS4wOTM3NSA2LjYyMzA1IDkuNDA0MyA2LjUwOTc3IDkuNjgxNjRDNi4zOTY0OCA5Ljk1NTA4IDYuMjM0MzggMTAuMTkxNCA2LjAyMzQ0IDEwLjM5MDZDNS44MTI1IDEwLjU4OTggNS41NTg1OSAxMC43NSA1LjI2MTcyIDEwLjg3MTFDNC45NjQ4NCAxMC45ODgzIDQuNjMyODEgMTEuMDY0NSA0LjI2NTYyIDExLjA5OTZWMTIuMjQ4SDMuMzMzOThWMTEuMDk5NkMzLjAwMTk1IDExLjA2ODQgMi42Nzk2OSAxMC45OTYxIDIuMzY3MTkgMTAuODgyOEMyLjA1NDY5IDEwLjc2NTYgMS43NzczNCAxMC41OTc3IDEuNTM1MTYgMTAuMzc4OUMxLjI5Njg4IDEwLjE2MDIgMS4xMDU0NyA5Ljg4NDc3IDAuOTYwOTM4IDkuNTUyNzNDMC44MTY0MDYgOS4yMTY4IDAuNzQ0MTQxIDguODE0NDUgMC43NDQxNDEgOC4zNDU3SDIuMzc4OTFDMi4zNzg5MSA4LjYyNjk1IDIuNDE5OTIgOC44NjMyOCAyLjUwMTk1IDkuMDU0NjlDMi41ODM5OCA5LjI0MjE5IDIuNjg5NDUgOS4zOTI1OCAyLjgxODM2IDkuNTA1ODZDMi45NTExNyA5LjYxNTIzIDMuMTAxNTYgOS42OTMzNiAzLjI2OTUzIDkuNzQwMjNDMy40Mzc1IDkuNzg3MTEgMy42MDkzOCA5LjgxMDU1IDMuNzg1MTYgOS44MTA1NUM0LjIwMzEyIDkuODEwNTUgNC41MTk1MyA5LjcxMjg5IDQuNzM0MzggOS41MTc1OEM0Ljk0OTIyIDkuMzIyMjcgNS4wNTY2NCA5LjA3MDMxIDUuMDU2NjQgOC43NjE3MlpNMTMuNDE4IDEyLjI3MTVIOC4wNzQyMlYxMUgxMy40MThWMTIuMjcxNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDMuOTUyNjQgNikiIGZpbGw9IndoaXRlIi8+Cjwvc3ZnPgo=);
  --jp-icon-text-editor: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8cGF0aCBjbGFzcz0ianAtdGV4dC1lZGl0b3ItaWNvbi1jb2xvciBqcC1pY29uLXNlbGVjdGFibGUiIGZpbGw9IiM2MTYxNjEiIGQ9Ik0xNSAxNUgzdjJoMTJ2LTJ6bTAtOEgzdjJoMTJWN3pNMyAxM2gxOHYtMkgzdjJ6bTAgOGgxOHYtMkgzdjJ6TTMgM3YyaDE4VjNIM3oiLz4KPC9zdmc+Cg==);
  --jp-icon-toc: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij4KICA8ZyBjbGFzcz0ianAtaWNvbjMganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjNjE2MTYxIj4KICAgIDxwYXRoIGQ9Ik03LDVIMjFWN0g3VjVNNywxM1YxMUgyMVYxM0g3TTQsNC41QTEuNSwxLjUgMCAwLDEgNS41LDZBMS41LDEuNSAwIDAsMSA0LDcuNUExLjUsMS41IDAgMCwxIDIuNSw2QTEuNSwxLjUgMCAwLDEgNCw0LjVNNCwxMC41QTEuNSwxLjUgMCAwLDEgNS41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMy41QTEuNSwxLjUgMCAwLDEgMi41LDEyQTEuNSwxLjUgMCAwLDEgNCwxMC41TTcsMTlWMTdIMjFWMTlIN000LDE2LjVBMS41LDEuNSAwIDAsMSA1LjUsMThBMS41LDEuNSAwIDAsMSA0LDE5LjVBMS41LDEuNSAwIDAsMSAyLjUsMThBMS41LDEuNSAwIDAsMSA0LDE2LjVaIiAvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-tree-view: url(data:image/svg+xml;base64,PHN2ZyBoZWlnaHQ9IjI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICAgIDxnIGNsYXNzPSJqcC1pY29uMyIgZmlsbD0iIzYxNjE2MSI+CiAgICAgICAgPHBhdGggZD0iTTAgMGgyNHYyNEgweiIgZmlsbD0ibm9uZSIvPgogICAgICAgIDxwYXRoIGQ9Ik0yMiAxMVYzaC03djNIOVYzSDJ2OGg3VjhoMnYxMGg0djNoN3YtOGgtN3YzaC0yVjhoMnYzeiIvPgogICAgPC9nPgo8L3N2Zz4K);
  --jp-icon-trusted: url(data:image/svg+xml;base64,PHN2ZyBmaWxsPSJub25lIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDI0IDI1Ij4KICAgIDxwYXRoIGNsYXNzPSJqcC1pY29uMiIgc3Ryb2tlPSIjMzMzMzMzIiBzdHJva2Utd2lkdGg9IjIiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDIgMykiIGQ9Ik0xLjg2MDk0IDExLjQ0MDlDMC44MjY0NDggOC43NzAyNyAwLjg2Mzc3OSA2LjA1NzY0IDEuMjQ5MDcgNC4xOTkzMkMyLjQ4MjA2IDMuOTMzNDcgNC4wODA2OCAzLjQwMzQ3IDUuNjAxMDIgMi44NDQ5QzcuMjM1NDkgMi4yNDQ0IDguODU2NjYgMS41ODE1IDkuOTg3NiAxLjA5NTM5QzExLjA1OTcgMS41ODM0MSAxMi42MDk0IDIuMjQ0NCAxNC4yMTggMi44NDMzOUMxNS43NTAzIDMuNDEzOTQgMTcuMzk5NSAzLjk1MjU4IDE4Ljc1MzkgNC4yMTM4NUMxOS4xMzY0IDYuMDcxNzcgMTkuMTcwOSA4Ljc3NzIyIDE4LjEzOSAxMS40NDA5QzE3LjAzMDMgMTQuMzAzMiAxNC42NjY4IDE3LjE4NDQgOS45OTk5OSAxOC45MzU0QzUuMzMzMiAxNy4xODQ0IDIuOTY5NjggMTQuMzAzMiAxLjg2MDk0IDExLjQ0MDlaIi8+CiAgICA8cGF0aCBjbGFzcz0ianAtaWNvbjIiIGZpbGw9IiMzMzMzMzMiIHN0cm9rZT0iIzMzMzMzMyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoOCA5Ljg2NzE5KSIgZD0iTTIuODYwMTUgNC44NjUzNUwwLjcyNjU0OSAyLjk5OTU5TDAgMy42MzA0NUwyLjg2MDE1IDYuMTMxNTdMOCAwLjYzMDg3Mkw3LjI3ODU3IDBMMi44NjAxNSA0Ljg2NTM1WiIvPgo8L3N2Zz4K);
  --jp-icon-undo: url(data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHdpZHRoPSIxNiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTEyLjUgOGMtMi42NSAwLTUuMDUuOTktNi45IDIuNkwyIDd2OWg5bC0zLjYyLTMuNjJjMS4zOS0xLjE2IDMuMTYtMS44OCA1LjEyLTEuODggMy41NCAwIDYuNTUgMi4zMSA3LjYgNS41bDIuMzctLjc4QzIxLjA4IDExLjAzIDE3LjE1IDggMTIuNSA4eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-user: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTYiIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KICA8ZyBjbGFzcz0ianAtaWNvbjMiIGZpbGw9IiM2MTYxNjEiPgogICAgPHBhdGggZD0iTTE2IDdhNCA0IDAgMTEtOCAwIDQgNCAwIDAxOCAwek0xMiAxNGE3IDcgMCAwMC03IDdoMTRhNyA3IDAgMDAtNy03eiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-users: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZlcnNpb249IjEuMSIgdmlld0JveD0iMCAwIDM2IDI0IiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciPgogPGcgY2xhc3M9ImpwLWljb24zIiB0cmFuc2Zvcm09Im1hdHJpeCgxLjczMjcgMCAwIDEuNzMyNyAtMy42MjgyIC4wOTk1NzcpIiBmaWxsPSIjNjE2MTYxIj4KICA8cGF0aCB0cmFuc2Zvcm09Im1hdHJpeCgxLjUsMCwwLDEuNSwwLC02KSIgZD0ibTEyLjE4NiA3LjUwOThjLTEuMDUzNSAwLTEuOTc1NyAwLjU2NjUtMi40Nzg1IDEuNDEwMiAwLjc1MDYxIDAuMzEyNzcgMS4zOTc0IDAuODI2NDggMS44NzMgMS40NzI3aDMuNDg2M2MwLTEuNTkyLTEuMjg4OS0yLjg4MjgtMi44ODA5LTIuODgyOHoiLz4KICA8cGF0aCBkPSJtMjAuNDY1IDIuMzg5NWEyLjE4ODUgMi4xODg1IDAgMCAxLTIuMTg4NCAyLjE4ODUgMi4xODg1IDIuMTg4NSAwIDAgMS0yLjE4ODUtMi4xODg1IDIuMTg4NSAyLjE4ODUgMCAwIDEgMi4xODg1LTIuMTg4NSAyLjE4ODUgMi4xODg1IDAgMCAxIDIuMTg4NCAyLjE4ODV6Ii8+CiAgPHBhdGggdHJhbnNmb3JtPSJtYXRyaXgoMS41LDAsMCwxLjUsMCwtNikiIGQ9Im0zLjU4OTggOC40MjE5Yy0xLjExMjYgMC0yLjAxMzcgMC45MDExMS0yLjAxMzcgMi4wMTM3aDIuODE0NWMwLjI2Nzk3LTAuMzczMDkgMC41OTA3LTAuNzA0MzUgMC45NTg5OC0wLjk3ODUyLTAuMzQ0MzMtMC42MTY4OC0xLjAwMzEtMS4wMzUyLTEuNzU5OC0xLjAzNTJ6Ii8+CiAgPHBhdGggZD0ibTYuOTE1NCA0LjYyM2ExLjUyOTQgMS41Mjk0IDAgMCAxLTEuNTI5NCAxLjUyOTQgMS41Mjk0IDEuNTI5NCAwIDAgMS0xLjUyOTQtMS41Mjk0IDEuNTI5NCAxLjUyOTQgMCAwIDEgMS41Mjk0LTEuNTI5NCAxLjUyOTQgMS41Mjk0IDAgMCAxIDEuNTI5NCAxLjUyOTR6Ii8+CiAgPHBhdGggZD0ibTYuMTM1IDEzLjUzNWMwLTMuMjM5MiAyLjYyNTktNS44NjUgNS44NjUtNS44NjUgMy4yMzkyIDAgNS44NjUgMi42MjU5IDUuODY1IDUuODY1eiIvPgogIDxjaXJjbGUgY3g9IjEyIiBjeT0iMy43Njg1IiByPSIyLjk2ODUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-vega: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbjEganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjMjEyMTIxIj4KICAgIDxwYXRoIGQ9Ik0xMC42IDUuNGwyLjItMy4ySDIuMnY3LjNsNC02LjZ6Ii8+CiAgICA8cGF0aCBkPSJNMTUuOCAyLjJsLTQuNCA2LjZMNyA2LjNsLTQuOCA4djUuNWgxNy42VjIuMmgtNHptLTcgMTUuNEg1LjV2LTQuNGgzLjN2NC40em00LjQgMEg5LjhWOS44aDMuNHY3Ljh6bTQuNCAwaC0zLjRWNi41aDMuNHYxMS4xeiIvPgogIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-word: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIwIDIwIj4KIDxnIGNsYXNzPSJqcC1pY29uMiIgZmlsbD0iIzQxNDE0MSI+CiAgPHJlY3QgeD0iMiIgeT0iMiIgd2lkdGg9IjE2IiBoZWlnaHQ9IjE2Ii8+CiA8L2c+CiA8ZyBjbGFzcz0ianAtaWNvbi1hY2NlbnQyIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSguNDMgLjA0MDEpIiBmaWxsPSIjZmZmIj4KICA8cGF0aCBkPSJtNC4xNCA4Ljc2cTAuMDY4Mi0xLjg5IDIuNDItMS44OSAxLjE2IDAgMS42OCAwLjQyIDAuNTY3IDAuNDEgMC41NjcgMS4xNnYzLjQ3cTAgMC40NjIgMC41MTQgMC40NjIgMC4xMDMgMCAwLjItMC4wMjMxdjAuNzE0cS0wLjM5OSAwLjEwMy0wLjY1MSAwLjEwMy0wLjQ1MiAwLTAuNjkzLTAuMjItMC4yMzEtMC4yLTAuMjg0LTAuNjYyLTAuOTU2IDAuODcyLTIgMC44NzItMC45MDMgMC0xLjQ3LTAuNDcyLTAuNTI1LTAuNDcyLTAuNTI1LTEuMjYgMC0wLjI2MiAwLjA0NTItMC40NzIgMC4wNTY3LTAuMjIgMC4xMTYtMC4zNzggMC4wNjgyLTAuMTY4IDAuMjMxLTAuMzA0IDAuMTU4LTAuMTQ3IDAuMjYyLTAuMjQyIDAuMTE2LTAuMDkxNCAwLjM2OC0wLjE2OCAwLjI2Mi0wLjA5MTQgMC4zOTktMC4xMjYgMC4xMzYtMC4wNDUyIDAuNDcyLTAuMTAzIDAuMzM2LTAuMDU3OCAwLjUwNC0wLjA3OTggMC4xNTgtMC4wMjMxIDAuNTY3LTAuMDc5OCAwLjU1Ni0wLjA2ODIgMC43NzctMC4yMjEgMC4yMi0wLjE1MiAwLjIyLTAuNDQxdi0wLjI1MnEwLTAuNDMtMC4zNTctMC42NjItMC4zMzYtMC4yMzEtMC45NzYtMC4yMzEtMC42NjIgMC0wLjk5OCAwLjI2Mi0wLjMzNiAwLjI1Mi0wLjM5OSAwLjc5OHptMS44OSAzLjY4cTAuNzg4IDAgMS4yNi0wLjQxIDAuNTA0LTAuNDIgMC41MDQtMC45MDN2LTEuMDVxLTAuMjg0IDAuMTM2LTAuODYxIDAuMjMxLTAuNTY3IDAuMDkxNC0wLjk4NyAwLjE1OC0wLjQyIDAuMDY4Mi0wLjc2NiAwLjMyNi0wLjMzNiAwLjI1Mi0wLjMzNiAwLjcwNHQwLjMwNCAwLjcwNCAwLjg2MSAwLjI1MnoiIHN0cm9rZS13aWR0aD0iMS4wNSIvPgogIDxwYXRoIGQ9Im0xMCA0LjU2aDAuOTQ1djMuMTVxMC42NTEtMC45NzYgMS44OS0wLjk3NiAxLjE2IDAgMS44OSAwLjg0IDAuNjgyIDAuODQgMC42ODIgMi4zMSAwIDEuNDctMC43MDQgMi40Mi0wLjcwNCAwLjg4Mi0xLjg5IDAuODgyLTEuMjYgMC0xLjg5LTEuMDJ2MC43NjZoLTAuODV6bTIuNjIgMy4wNHEtMC43NDYgMC0xLjE2IDAuNjQtMC40NTIgMC42My0wLjQ1MiAxLjY4IDAgMS4wNSAwLjQ1MiAxLjY4dDEuMTYgMC42M3EwLjc3NyAwIDEuMjYtMC42MyAwLjQ5NC0wLjY0IDAuNDk0LTEuNjggMC0xLjA1LTAuNDcyLTEuNjgtMC40NjItMC42NC0xLjI2LTAuNjR6IiBzdHJva2Utd2lkdGg9IjEuMDUiLz4KICA8cGF0aCBkPSJtMi43MyAxNS44IDEzLjYgMC4wMDgxYzAuMDA2OSAwIDAtMi42IDAtMi42IDAtMC4wMDc4LTEuMTUgMC0xLjE1IDAtMC4wMDY5IDAtMC4wMDgzIDEuNS0wLjAwODMgMS41LTJlLTMgLTAuMDAxNC0xMS4zLTAuMDAxNC0xMS4zLTAuMDAxNGwtMC4wMDU5Mi0xLjVjMC0wLjAwNzgtMS4xNyAwLjAwMTMtMS4xNyAwLjAwMTN6IiBzdHJva2Utd2lkdGg9Ii45NzUiLz4KIDwvZz4KPC9zdmc+Cg==);
  --jp-icon-yaml: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgdmlld0JveD0iMCAwIDIyIDIyIj4KICA8ZyBjbGFzcz0ianAtaWNvbi1jb250cmFzdDIganAtaWNvbi1zZWxlY3RhYmxlIiBmaWxsPSIjRDgxQjYwIj4KICAgIDxwYXRoIGQ9Ik03LjIgMTguNnYtNS40TDMgNS42aDMuM2wxLjQgMy4xYy4zLjkuNiAxLjYgMSAyLjUuMy0uOC42LTEuNiAxLTIuNWwxLjQtMy4xaDMuNGwtNC40IDcuNnY1LjVsLTIuOS0uMXoiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxNi41IiByPSIyLjEiLz4KICAgIDxjaXJjbGUgY2xhc3M9InN0MCIgY3g9IjE3LjYiIGN5PSIxMSIgcj0iMi4xIi8+CiAgPC9nPgo8L3N2Zz4K);
}

/* Icon CSS class declarations */

.jp-AddAboveIcon {
  background-image: var(--jp-icon-add-above);
}

.jp-AddBelowIcon {
  background-image: var(--jp-icon-add-below);
}

.jp-AddIcon {
  background-image: var(--jp-icon-add);
}

.jp-BellIcon {
  background-image: var(--jp-icon-bell);
}

.jp-BugDotIcon {
  background-image: var(--jp-icon-bug-dot);
}

.jp-BugIcon {
  background-image: var(--jp-icon-bug);
}

.jp-BuildIcon {
  background-image: var(--jp-icon-build);
}

.jp-CaretDownEmptyIcon {
  background-image: var(--jp-icon-caret-down-empty);
}

.jp-CaretDownEmptyThinIcon {
  background-image: var(--jp-icon-caret-down-empty-thin);
}

.jp-CaretDownIcon {
  background-image: var(--jp-icon-caret-down);
}

.jp-CaretLeftIcon {
  background-image: var(--jp-icon-caret-left);
}

.jp-CaretRightIcon {
  background-image: var(--jp-icon-caret-right);
}

.jp-CaretUpEmptyThinIcon {
  background-image: var(--jp-icon-caret-up-empty-thin);
}

.jp-CaretUpIcon {
  background-image: var(--jp-icon-caret-up);
}

.jp-CaseSensitiveIcon {
  background-image: var(--jp-icon-case-sensitive);
}

.jp-CheckIcon {
  background-image: var(--jp-icon-check);
}

.jp-CircleEmptyIcon {
  background-image: var(--jp-icon-circle-empty);
}

.jp-CircleIcon {
  background-image: var(--jp-icon-circle);
}

.jp-ClearIcon {
  background-image: var(--jp-icon-clear);
}

.jp-CloseIcon {
  background-image: var(--jp-icon-close);
}

.jp-CodeCheckIcon {
  background-image: var(--jp-icon-code-check);
}

.jp-CodeIcon {
  background-image: var(--jp-icon-code);
}

.jp-CollapseAllIcon {
  background-image: var(--jp-icon-collapse-all);
}

.jp-ConsoleIcon {
  background-image: var(--jp-icon-console);
}

.jp-CopyIcon {
  background-image: var(--jp-icon-copy);
}

.jp-CopyrightIcon {
  background-image: var(--jp-icon-copyright);
}

.jp-CutIcon {
  background-image: var(--jp-icon-cut);
}

.jp-DeleteIcon {
  background-image: var(--jp-icon-delete);
}

.jp-DownloadIcon {
  background-image: var(--jp-icon-download);
}

.jp-DuplicateIcon {
  background-image: var(--jp-icon-duplicate);
}

.jp-EditIcon {
  background-image: var(--jp-icon-edit);
}

.jp-EllipsesIcon {
  background-image: var(--jp-icon-ellipses);
}

.jp-ErrorIcon {
  background-image: var(--jp-icon-error);
}

.jp-ExpandAllIcon {
  background-image: var(--jp-icon-expand-all);
}

.jp-ExtensionIcon {
  background-image: var(--jp-icon-extension);
}

.jp-FastForwardIcon {
  background-image: var(--jp-icon-fast-forward);
}

.jp-FileIcon {
  background-image: var(--jp-icon-file);
}

.jp-FileUploadIcon {
  background-image: var(--jp-icon-file-upload);
}

.jp-FilterDotIcon {
  background-image: var(--jp-icon-filter-dot);
}

.jp-FilterIcon {
  background-image: var(--jp-icon-filter);
}

.jp-FilterListIcon {
  background-image: var(--jp-icon-filter-list);
}

.jp-FolderFavoriteIcon {
  background-image: var(--jp-icon-folder-favorite);
}

.jp-FolderIcon {
  background-image: var(--jp-icon-folder);
}

.jp-HomeIcon {
  background-image: var(--jp-icon-home);
}

.jp-Html5Icon {
  background-image: var(--jp-icon-html5);
}

.jp-ImageIcon {
  background-image: var(--jp-icon-image);
}

.jp-InfoIcon {
  background-image: var(--jp-icon-info);
}

.jp-InspectorIcon {
  background-image: var(--jp-icon-inspector);
}

.jp-JsonIcon {
  background-image: var(--jp-icon-json);
}

.jp-JuliaIcon {
  background-image: var(--jp-icon-julia);
}

.jp-JupyterFaviconIcon {
  background-image: var(--jp-icon-jupyter-favicon);
}

.jp-JupyterIcon {
  background-image: var(--jp-icon-jupyter);
}

.jp-JupyterlabWordmarkIcon {
  background-image: var(--jp-icon-jupyterlab-wordmark);
}

.jp-KernelIcon {
  background-image: var(--jp-icon-kernel);
}

.jp-KeyboardIcon {
  background-image: var(--jp-icon-keyboard);
}

.jp-LaunchIcon {
  background-image: var(--jp-icon-launch);
}

.jp-LauncherIcon {
  background-image: var(--jp-icon-launcher);
}

.jp-LineFormIcon {
  background-image: var(--jp-icon-line-form);
}

.jp-LinkIcon {
  background-image: var(--jp-icon-link);
}

.jp-ListIcon {
  background-image: var(--jp-icon-list);
}

.jp-MarkdownIcon {
  background-image: var(--jp-icon-markdown);
}

.jp-MoveDownIcon {
  background-image: var(--jp-icon-move-down);
}

.jp-MoveUpIcon {
  background-image: var(--jp-icon-move-up);
}

.jp-NewFolderIcon {
  background-image: var(--jp-icon-new-folder);
}

.jp-NotTrustedIcon {
  background-image: var(--jp-icon-not-trusted);
}

.jp-NotebookIcon {
  background-image: var(--jp-icon-notebook);
}

.jp-NumberingIcon {
  background-image: var(--jp-icon-numbering);
}

.jp-OfflineBoltIcon {
  background-image: var(--jp-icon-offline-bolt);
}

.jp-PaletteIcon {
  background-image: var(--jp-icon-palette);
}

.jp-PasteIcon {
  background-image: var(--jp-icon-paste);
}

.jp-PdfIcon {
  background-image: var(--jp-icon-pdf);
}

.jp-PythonIcon {
  background-image: var(--jp-icon-python);
}

.jp-RKernelIcon {
  background-image: var(--jp-icon-r-kernel);
}

.jp-ReactIcon {
  background-image: var(--jp-icon-react);
}

.jp-RedoIcon {
  background-image: var(--jp-icon-redo);
}

.jp-RefreshIcon {
  background-image: var(--jp-icon-refresh);
}

.jp-RegexIcon {
  background-image: var(--jp-icon-regex);
}

.jp-RunIcon {
  background-image: var(--jp-icon-run);
}

.jp-RunningIcon {
  background-image: var(--jp-icon-running);
}

.jp-SaveIcon {
  background-image: var(--jp-icon-save);
}

.jp-SearchIcon {
  background-image: var(--jp-icon-search);
}

.jp-SettingsIcon {
  background-image: var(--jp-icon-settings);
}

.jp-ShareIcon {
  background-image: var(--jp-icon-share);
}

.jp-SpreadsheetIcon {
  background-image: var(--jp-icon-spreadsheet);
}

.jp-StopIcon {
  background-image: var(--jp-icon-stop);
}

.jp-TabIcon {
  background-image: var(--jp-icon-tab);
}

.jp-TableRowsIcon {
  background-image: var(--jp-icon-table-rows);
}

.jp-TagIcon {
  background-image: var(--jp-icon-tag);
}

.jp-TerminalIcon {
  background-image: var(--jp-icon-terminal);
}

.jp-TextEditorIcon {
  background-image: var(--jp-icon-text-editor);
}

.jp-TocIcon {
  background-image: var(--jp-icon-toc);
}

.jp-TreeViewIcon {
  background-image: var(--jp-icon-tree-view);
}

.jp-TrustedIcon {
  background-image: var(--jp-icon-trusted);
}

.jp-UndoIcon {
  background-image: var(--jp-icon-undo);
}

.jp-UserIcon {
  background-image: var(--jp-icon-user);
}

.jp-UsersIcon {
  background-image: var(--jp-icon-users);
}

.jp-VegaIcon {
  background-image: var(--jp-icon-vega);
}

.jp-WordIcon {
  background-image: var(--jp-icon-word);
}

.jp-YamlIcon {
  background-image: var(--jp-icon-yaml);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * (DEPRECATED) Support for consuming icons as CSS background images
 */

.jp-Icon,
.jp-MaterialIcon {
  background-position: center;
  background-repeat: no-repeat;
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-cover {
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

/**
 * (DEPRECATED) Support for specific CSS icon sizes
 */

.jp-Icon-16 {
  background-size: 16px;
  min-width: 16px;
  min-height: 16px;
}

.jp-Icon-18 {
  background-size: 18px;
  min-width: 18px;
  min-height: 18px;
}

.jp-Icon-20 {
  background-size: 20px;
  min-width: 20px;
  min-height: 20px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.lm-TabBar .lm-TabBar-addButton {
  align-items: center;
  display: flex;
  padding: 4px;
  padding-bottom: 5px;
  margin-right: 1px;
  background-color: var(--jp-layout-color2);
}

.lm-TabBar .lm-TabBar-addButton:hover {
  background-color: var(--jp-layout-color1);
}

.lm-DockPanel-tabBar .lm-TabBar-tab {
  width: var(--jp-private-horizontal-tab-width);
}

.lm-DockPanel-tabBar .lm-TabBar-content {
  flex: unset;
}

.lm-DockPanel-tabBar[data-orientation='horizontal'] {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for icons as inline SVG HTMLElements
 */

/* recolor the primary elements of an icon */
.jp-icon0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-accent0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-accent1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-accent2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-accent3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-accent4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-accent0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-accent1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-accent2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-accent3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-accent4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-none[fill] {
  fill: none;
}

.jp-icon-none[stroke] {
  stroke: none;
}

/* brand icon colors. Same for light and dark */
.jp-icon-brand0[fill] {
  fill: var(--jp-brand-color0);
}

.jp-icon-brand1[fill] {
  fill: var(--jp-brand-color1);
}

.jp-icon-brand2[fill] {
  fill: var(--jp-brand-color2);
}

.jp-icon-brand3[fill] {
  fill: var(--jp-brand-color3);
}

.jp-icon-brand4[fill] {
  fill: var(--jp-brand-color4);
}

.jp-icon-brand0[stroke] {
  stroke: var(--jp-brand-color0);
}

.jp-icon-brand1[stroke] {
  stroke: var(--jp-brand-color1);
}

.jp-icon-brand2[stroke] {
  stroke: var(--jp-brand-color2);
}

.jp-icon-brand3[stroke] {
  stroke: var(--jp-brand-color3);
}

.jp-icon-brand4[stroke] {
  stroke: var(--jp-brand-color4);
}

/* warn icon colors. Same for light and dark */
.jp-icon-warn0[fill] {
  fill: var(--jp-warn-color0);
}

.jp-icon-warn1[fill] {
  fill: var(--jp-warn-color1);
}

.jp-icon-warn2[fill] {
  fill: var(--jp-warn-color2);
}

.jp-icon-warn3[fill] {
  fill: var(--jp-warn-color3);
}

.jp-icon-warn0[stroke] {
  stroke: var(--jp-warn-color0);
}

.jp-icon-warn1[stroke] {
  stroke: var(--jp-warn-color1);
}

.jp-icon-warn2[stroke] {
  stroke: var(--jp-warn-color2);
}

.jp-icon-warn3[stroke] {
  stroke: var(--jp-warn-color3);
}

/* icon colors that contrast well with each other and most backgrounds */
.jp-icon-contrast0[fill] {
  fill: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[fill] {
  fill: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[fill] {
  fill: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[fill] {
  fill: var(--jp-icon-contrast-color3);
}

.jp-icon-contrast0[stroke] {
  stroke: var(--jp-icon-contrast-color0);
}

.jp-icon-contrast1[stroke] {
  stroke: var(--jp-icon-contrast-color1);
}

.jp-icon-contrast2[stroke] {
  stroke: var(--jp-icon-contrast-color2);
}

.jp-icon-contrast3[stroke] {
  stroke: var(--jp-icon-contrast-color3);
}

.jp-icon-dot[fill] {
  fill: var(--jp-warn-color0);
}

.jp-jupyter-icon-color[fill] {
  fill: var(--jp-jupyter-icon-color, var(--jp-warn-color0));
}

.jp-notebook-icon-color[fill] {
  fill: var(--jp-notebook-icon-color, var(--jp-warn-color0));
}

.jp-json-icon-color[fill] {
  fill: var(--jp-json-icon-color, var(--jp-warn-color1));
}

.jp-console-icon-color[fill] {
  fill: var(--jp-console-icon-color, white);
}

.jp-console-icon-background-color[fill] {
  fill: var(--jp-console-icon-background-color, var(--jp-brand-color1));
}

.jp-terminal-icon-color[fill] {
  fill: var(--jp-terminal-icon-color, var(--jp-layout-color2));
}

.jp-terminal-icon-background-color[fill] {
  fill: var(
    --jp-terminal-icon-background-color,
    var(--jp-inverse-layout-color2)
  );
}

.jp-text-editor-icon-color[fill] {
  fill: var(--jp-text-editor-icon-color, var(--jp-inverse-layout-color3));
}

.jp-inspector-icon-color[fill] {
  fill: var(--jp-inspector-icon-color, var(--jp-inverse-layout-color3));
}

/* CSS for icons in selected filebrowser listing items */
.jp-DirListing-item.jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

.jp-DirListing-item.jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* stylelint-disable selector-max-class, selector-max-compound-selectors */

/**
* TODO: come up with non css-hack solution for showing the busy icon on top
*  of the close icon
* CSS for complex behavior of close icon of tabs in the main area tabbar
*/
.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon3[fill] {
  fill: none;
}

.lm-DockPanel-tabBar
  .lm-TabBar-tab.lm-mod-closable.jp-mod-dirty
  > .lm-TabBar-tabCloseIcon
  > :not(:hover)
  > .jp-icon-busy[fill] {
  fill: var(--jp-inverse-layout-color3);
}

/* stylelint-enable selector-max-class, selector-max-compound-selectors */

/* CSS for icons in status bar */
#jp-main-statusbar .jp-mod-selected .jp-icon-selectable[fill] {
  fill: #fff;
}

#jp-main-statusbar .jp-mod-selected .jp-icon-selectable-inverse[fill] {
  fill: var(--jp-brand-color1);
}

/* special handling for splash icon CSS. While the theme CSS reloads during
   splash, the splash icon can loose theming. To prevent that, we set a
   default for its color variable */
:root {
  --jp-warn-color0: var(--md-orange-700);
}

/* not sure what to do with this one, used in filebrowser listing */
.jp-DragIcon {
  margin-right: 4px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/**
 * Support for alt colors for icons as inline SVG HTMLElements
 */

/* alt recolor the primary elements of an icon */
.jp-icon-alt .jp-icon0[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-alt .jp-icon0[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-alt .jp-icon1[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-alt .jp-icon2[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-alt .jp-icon3[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-alt .jp-icon4[stroke] {
  stroke: var(--jp-layout-color4);
}

/* alt recolor the accent elements of an icon */
.jp-icon-alt .jp-icon-accent0[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-alt .jp-icon-accent0[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-alt .jp-icon-accent1[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-alt .jp-icon-accent2[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-alt .jp-icon-accent3[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-alt .jp-icon-accent4[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-icon-hoverShow:not(:hover) .jp-icon-hoverShow-content {
  display: none !important;
}

/**
 * Support for hover colors for icons as inline SVG HTMLElements
 */

/**
 * regular colors
 */

/* recolor the primary elements of an icon */
.jp-icon-hover :hover .jp-icon0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/* recolor the accent elements of an icon */
.jp-icon-hover :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* set the color of an icon to transparent */
.jp-icon-hover :hover .jp-icon-none-hover[fill] {
  fill: none;
}

.jp-icon-hover :hover .jp-icon-none-hover[stroke] {
  stroke: none;
}

/**
 * inverse colors
 */

/* inverse recolor the primary elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[fill] {
  fill: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[fill] {
  fill: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[fill] {
  fill: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[fill] {
  fill: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[fill] {
  fill: var(--jp-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon0-hover[stroke] {
  stroke: var(--jp-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon1-hover[stroke] {
  stroke: var(--jp-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon2-hover[stroke] {
  stroke: var(--jp-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon3-hover[stroke] {
  stroke: var(--jp-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon4-hover[stroke] {
  stroke: var(--jp-layout-color4);
}

/* inverse recolor the accent elements of an icon */
.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[fill] {
  fill: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[fill] {
  fill: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[fill] {
  fill: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[fill] {
  fill: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[fill] {
  fill: var(--jp-inverse-layout-color4);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent0-hover[stroke] {
  stroke: var(--jp-inverse-layout-color0);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent1-hover[stroke] {
  stroke: var(--jp-inverse-layout-color1);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent2-hover[stroke] {
  stroke: var(--jp-inverse-layout-color2);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent3-hover[stroke] {
  stroke: var(--jp-inverse-layout-color3);
}

.jp-icon-hover.jp-icon-alt :hover .jp-icon-accent4-hover[stroke] {
  stroke: var(--jp-inverse-layout-color4);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-IFrame {
  width: 100%;
  height: 100%;
}

.jp-IFrame > iframe {
  border: none;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-IFrame {
  position: relative;
}

body.lm-mod-override-cursor .jp-IFrame::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-HoverBox {
  position: fixed;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FormGroup-content fieldset {
  border: none;
  padding: 0;
  min-width: 0;
  width: 100%;
}

/* stylelint-disable selector-max-type */

.jp-FormGroup-content fieldset .jp-inputFieldWrapper input,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper select,
.jp-FormGroup-content fieldset .jp-inputFieldWrapper textarea {
  font-size: var(--jp-content-font-size2);
  border-color: var(--jp-input-border-color);
  border-style: solid;
  border-radius: var(--jp-border-radius);
  border-width: 1px;
  padding: 6px 8px;
  background: none;
  color: var(--jp-ui-font-color0);
  height: inherit;
}

.jp-FormGroup-content fieldset input[type='checkbox'] {
  position: relative;
  top: 2px;
  margin-left: 0;
}

.jp-FormGroup-content button.jp-mod-styled {
  cursor: pointer;
}

.jp-FormGroup-content .checkbox label {
  cursor: pointer;
  font-size: var(--jp-content-font-size1);
}

.jp-FormGroup-content .jp-root > fieldset > legend {
  display: none;
}

.jp-FormGroup-content .jp-root > fieldset > p {
  display: none;
}

/** copy of `input.jp-mod-styled:focus` style */
.jp-FormGroup-content fieldset input:focus,
.jp-FormGroup-content fieldset select:focus {
  -moz-outline-radius: unset;
  outline: var(--jp-border-width) solid var(--md-blue-500);
  outline-offset: -1px;
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-FormGroup-content fieldset input:hover:not(:focus),
.jp-FormGroup-content fieldset select:hover:not(:focus) {
  background-color: var(--jp-border-color2);
}

/* stylelint-enable selector-max-type */

.jp-FormGroup-content .checkbox .field-description {
  /* Disable default description field for checkbox:
   because other widgets do not have description fields,
   we add descriptions to each widget on the field level.
  */
  display: none;
}

.jp-FormGroup-content #root__description {
  display: none;
}

.jp-FormGroup-content .jp-modifiedIndicator {
  width: 5px;
  background-color: var(--jp-brand-color2);
  margin-top: 0;
  margin-left: calc(var(--jp-private-settingeditor-modifier-indent) * -1);
  flex-shrink: 0;
}

.jp-FormGroup-content .jp-modifiedIndicator.jp-errorIndicator {
  background-color: var(--jp-error-color0);
  margin-right: 0.5em;
}

/* RJSF ARRAY style */

.jp-arrayFieldWrapper legend {
  font-size: var(--jp-content-font-size2);
  color: var(--jp-ui-font-color0);
  flex-basis: 100%;
  padding: 4px 0;
  font-weight: var(--jp-content-heading-font-weight);
  border-bottom: 1px solid var(--jp-border-color2);
}

.jp-arrayFieldWrapper .field-description {
  padding: 4px 0;
  white-space: pre-wrap;
}

.jp-arrayFieldWrapper .array-item {
  width: 100%;
  border: 1px solid var(--jp-border-color2);
  border-radius: 4px;
  margin: 4px;
}

.jp-ArrayOperations {
  display: flex;
  margin-left: 8px;
}

.jp-ArrayOperationsButton {
  margin: 2px;
}

.jp-ArrayOperationsButton .jp-icon3[fill] {
  fill: var(--jp-ui-font-color0);
}

button.jp-ArrayOperationsButton.jp-mod-styled:disabled {
  cursor: not-allowed;
  opacity: 0.5;
}

/* RJSF form validation error */

.jp-FormGroup-content .validationErrors {
  color: var(--jp-error-color0);
}

/* Hide panel level error as duplicated the field level error */
.jp-FormGroup-content .panel.errors {
  display: none;
}

/* RJSF normal content (settings-editor) */

.jp-FormGroup-contentNormal {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-FormGroup-contentItem {
  margin-left: 7px;
  color: var(--jp-ui-font-color0);
}

.jp-FormGroup-contentNormal .jp-FormGroup-description {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-default {
  flex-basis: 100%;
  padding: 4px 7px;
}

.jp-FormGroup-contentNormal .jp-FormGroup-fieldLabel {
  font-size: var(--jp-content-font-size1);
  font-weight: normal;
  min-width: 120px;
}

.jp-FormGroup-contentNormal fieldset:not(:first-child) {
  margin-left: 7px;
}

.jp-FormGroup-contentNormal .field-array-of-string .array-item {
  /* Display `jp-ArrayOperations` buttons side-by-side with content except
    for small screens where flex-wrap will place them one below the other.
  */
  display: flex;
  align-items: center;
  flex-wrap: wrap;
}

.jp-FormGroup-contentNormal .jp-objectFieldWrapper .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

/* RJSF compact content (metadata-form) */

.jp-FormGroup-content.jp-FormGroup-contentCompact {
  width: 100%;
}

.jp-FormGroup-contentCompact .form-group {
  display: flex;
  padding: 0.5em 0.2em 0.5em 0;
}

.jp-FormGroup-contentCompact
  .jp-FormGroup-compactTitle
  .jp-FormGroup-description {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color2);
}

.jp-FormGroup-contentCompact .jp-FormGroup-fieldLabel {
  padding-bottom: 0.3em;
}

.jp-FormGroup-contentCompact .jp-inputFieldWrapper .form-control {
  width: 100%;
  box-sizing: border-box;
}

.jp-FormGroup-contentCompact .jp-arrayFieldWrapper .jp-FormGroup-compactTitle {
  padding-bottom: 7px;
}

.jp-FormGroup-contentCompact
  .jp-objectFieldWrapper
  .jp-objectFieldWrapper
  .form-group {
  padding: 2px 8px 2px var(--jp-private-settingeditor-modifier-indent);
  margin-top: 2px;
}

.jp-FormGroup-contentCompact ul.error-detail {
  margin-block-start: 0.5em;
  margin-block-end: 0.5em;
  padding-inline-start: 1em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-SidePanel {
  display: flex;
  flex-direction: column;
  min-width: var(--jp-sidebar-min-width);
  overflow-y: auto;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);
  font-size: var(--jp-ui-font-size1);
}

.jp-SidePanel-header {
  flex: 0 0 auto;
  display: flex;
  border-bottom: var(--jp-border-width) solid var(--jp-border-color2);
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin: 0;
  padding: 2px;
  text-transform: uppercase;
}

.jp-SidePanel-toolbar {
  flex: 0 0 auto;
}

.jp-SidePanel-content {
  flex: 1 1 auto;
}

.jp-SidePanel-toolbar,
.jp-AccordionPanel-toolbar {
  height: var(--jp-private-toolbar-height);
}

.jp-SidePanel-toolbar.jp-Toolbar-micro {
  display: none;
}

.lm-AccordionPanel .jp-AccordionPanel-title {
  box-sizing: border-box;
  line-height: 25px;
  margin: 0;
  display: flex;
  align-items: center;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  font-size: var(--jp-ui-font-size0);
}

.jp-AccordionPanel-title {
  cursor: pointer;
  user-select: none;
  -moz-user-select: none;
  -webkit-user-select: none;
  text-transform: uppercase;
}

.lm-AccordionPanel[data-orientation='horizontal'] > .jp-AccordionPanel-title {
  /* Title is rotated for horizontal accordion panel using CSS */
  display: block;
  transform-origin: top left;
  transform: rotate(-90deg) translate(-100%);
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleLabel {
  user-select: none;
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}

.jp-AccordionPanel-title .lm-AccordionPanel-titleCollapser {
  transform: rotate(-90deg);
  margin: auto 0;
  height: 16px;
}

.jp-AccordionPanel-title.lm-mod-expanded .lm-AccordionPanel-titleCollapser {
  transform: rotate(0deg);
}

.lm-AccordionPanel .jp-AccordionPanel-toolbar {
  background: none;
  box-shadow: none;
  border: none;
  margin-left: auto;
}

.lm-AccordionPanel .lm-SplitPanel-handle:hover {
  background: var(--jp-layout-color3);
}

.jp-text-truncated {
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Spinner {
  position: absolute;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-layout-color0);
  outline: none;
}

.jp-SpinnerContent {
  font-size: 10px;
  margin: 50px auto;
  text-indent: -9999em;
  width: 3em;
  height: 3em;
  border-radius: 50%;
  background: var(--jp-brand-color3);
  background: linear-gradient(
    to right,
    #f37626 10%,
    rgba(255, 255, 255, 0) 42%
  );
  position: relative;
  animation: load3 1s infinite linear, fadeIn 1s;
}

.jp-SpinnerContent::before {
  width: 50%;
  height: 50%;
  background: #f37626;
  border-radius: 100% 0 0;
  position: absolute;
  top: 0;
  left: 0;
  content: '';
}

.jp-SpinnerContent::after {
  background: var(--jp-layout-color0);
  width: 75%;
  height: 75%;
  border-radius: 50%;
  content: '';
  margin: auto;
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
}

@keyframes fadeIn {
  0% {
    opacity: 0;
  }

  100% {
    opacity: 1;
  }
}

@keyframes load3 {
  0% {
    transform: rotate(0deg);
  }

  100% {
    transform: rotate(360deg);
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

button.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: none;
  box-sizing: border-box;
  text-align: center;
  line-height: 32px;
  height: 32px;
  padding: 0 12px;
  letter-spacing: 0.8px;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input.jp-mod-styled {
  background: var(--jp-input-background);
  height: 28px;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color1);
  padding-left: 7px;
  padding-right: 7px;
  font-size: var(--jp-ui-font-size2);
  color: var(--jp-ui-font-color0);
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

input[type='checkbox'].jp-mod-styled {
  appearance: checkbox;
  -webkit-appearance: checkbox;
  -moz-appearance: checkbox;
  height: auto;
}

input.jp-mod-styled:focus {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-select-wrapper {
  display: flex;
  position: relative;
  flex-direction: column;
  padding: 1px;
  background-color: var(--jp-layout-color1);
  box-sizing: border-box;
  margin-bottom: 12px;
}

.jp-select-wrapper:not(.multiple) {
  height: 28px;
}

.jp-select-wrapper.jp-mod-focused select.jp-mod-styled {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-input-active-background);
}

select.jp-mod-styled:hover {
  cursor: pointer;
  color: var(--jp-ui-font-color0);
  background-color: var(--jp-input-hover-background);
  box-shadow: inset 0 0 1px rgba(0, 0, 0, 0.5);
}

select.jp-mod-styled {
  flex: 1 1 auto;
  width: 100%;
  font-size: var(--jp-ui-font-size2);
  background: var(--jp-input-background);
  color: var(--jp-ui-font-color0);
  padding: 0 25px 0 8px;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
}

select.jp-mod-styled:not([multiple]) {
  height: 32px;
}

select.jp-mod-styled[multiple] {
  max-height: 200px;
  overflow-y: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-switch {
  display: flex;
  align-items: center;
  padding-left: 4px;
  padding-right: 4px;
  font-size: var(--jp-ui-font-size1);
  background-color: transparent;
  color: var(--jp-ui-font-color1);
  border: none;
  height: 20px;
}

.jp-switch:hover {
  background-color: var(--jp-layout-color2);
}

.jp-switch-label {
  margin-right: 5px;
  font-family: var(--jp-ui-font-family);
}

.jp-switch-track {
  cursor: pointer;
  background-color: var(--jp-switch-color, var(--jp-border-color1));
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 34px;
  height: 16px;
  width: 35px;
  position: relative;
}

.jp-switch-track::before {
  content: '';
  position: absolute;
  height: 10px;
  width: 10px;
  margin: 3px;
  left: 0;
  background-color: var(--jp-ui-inverse-font-color1);
  -webkit-transition: 0.4s;
  transition: 0.4s;
  border-radius: 50%;
}

.jp-switch[aria-checked='true'] .jp-switch-track {
  background-color: var(--jp-switch-true-position-color, var(--jp-warn-color0));
}

.jp-switch[aria-checked='true'] .jp-switch-track::before {
  /* track width (35) - margins (3 + 3) - thumb width (10) */
  left: 19px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toolbar-height: calc(
    28px + var(--jp-border-width)
  ); /* leave 28px for content */
}

.jp-Toolbar {
  color: var(--jp-ui-font-color1);
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: 2px;
  z-index: 8;
  overflow-x: hidden;
}

/* Toolbar items */

.jp-Toolbar > .jp-Toolbar-item.jp-Toolbar-spacer {
  flex-grow: 1;
  flex-shrink: 1;
}

.jp-Toolbar-item.jp-Toolbar-kernelStatus {
  display: inline-block;
  width: 32px;
  background-repeat: no-repeat;
  background-position: center;
  background-size: 16px;
}

.jp-Toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  display: flex;
  padding-left: 1px;
  padding-right: 1px;
  font-size: var(--jp-ui-font-size1);
  line-height: var(--jp-private-toolbar-height);
  height: 100%;
}

/* Toolbar buttons */

/* This is the div we use to wrap the react component into a Widget */
div.jp-ToolbarButton {
  color: transparent;
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0;
  margin: 0;
}

button.jp-ToolbarButtonComponent {
  background: var(--jp-layout-color1);
  border: none;
  box-sizing: border-box;
  outline: none;
  appearance: none;
  -webkit-appearance: none;
  -moz-appearance: none;
  padding: 0 6px;
  margin: 0;
  height: 24px;
  border-radius: var(--jp-border-radius);
  display: flex;
  align-items: center;
  text-align: center;
  font-size: 14px;
  min-width: unset;
  min-height: unset;
}

button.jp-ToolbarButtonComponent:disabled {
  opacity: 0.4;
}

button.jp-ToolbarButtonComponent > span {
  padding: 0;
  flex: 0 0 auto;
}

button.jp-ToolbarButtonComponent .jp-ToolbarButtonComponent-label {
  font-size: var(--jp-ui-font-size1);
  line-height: 100%;
  padding-left: 2px;
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar.jp-Toolbar-micro {
  padding: 0;
  min-height: 0;
}

#jp-main-dock-panel[data-mode='single-document']
  .jp-MainAreaWidget
  > .jp-Toolbar {
  border: none;
  box-shadow: none;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-WindowedPanel-outer {
  position: relative;
  overflow-y: auto;
}

.jp-WindowedPanel-inner {
  position: relative;
}

.jp-WindowedPanel-window {
  position: absolute;
  left: 0;
  right: 0;
  overflow: visible;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/* Sibling imports */

body {
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
}

/* Disable native link decoration styles everywhere outside of dialog boxes */
a {
  text-decoration: unset;
  color: unset;
}

a:hover {
  text-decoration: unset;
  color: unset;
}

/* Accessibility for links inside dialog box text */
.jp-Dialog-content a {
  text-decoration: revert;
  color: var(--jp-content-link-color);
}

.jp-Dialog-content a:hover {
  text-decoration: revert;
}

/* Styles for ui-components */
.jp-Button {
  color: var(--jp-ui-font-color2);
  border-radius: var(--jp-border-radius);
  padding: 0 12px;
  font-size: var(--jp-ui-font-size1);

  /* Copy from blueprint 3 */
  display: inline-flex;
  flex-direction: row;
  border: none;
  cursor: pointer;
  align-items: center;
  justify-content: center;
  text-align: left;
  vertical-align: middle;
  min-height: 30px;
  min-width: 30px;
}

.jp-Button:disabled {
  cursor: not-allowed;
}

.jp-Button:empty {
  padding: 0 !important;
}

.jp-Button.jp-mod-small {
  min-height: 24px;
  min-width: 24px;
  font-size: 12px;
  padding: 0 7px;
}

/* Use our own theme for hover styles */
.jp-Button.jp-mod-minimal:hover {
  background-color: var(--jp-layout-color2);
}

.jp-Button.jp-mod-minimal {
  background: none;
}

.jp-InputGroup {
  display: block;
  position: relative;
}

.jp-InputGroup input {
  box-sizing: border-box;
  border: none;
  border-radius: 0;
  background-color: transparent;
  color: var(--jp-ui-font-color0);
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
  padding-bottom: 0;
  padding-top: 0;
  padding-left: 10px;
  padding-right: 28px;
  position: relative;
  width: 100%;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  font-size: 14px;
  font-weight: 400;
  height: 30px;
  line-height: 30px;
  outline: none;
  vertical-align: middle;
}

.jp-InputGroup input:focus {
  box-shadow: inset 0 0 0 var(--jp-border-width)
      var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-InputGroup input:disabled {
  cursor: not-allowed;
  resize: block;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input:disabled ~ span {
  cursor: not-allowed;
  color: var(--jp-ui-font-color2);
}

.jp-InputGroup input::placeholder,
input::placeholder {
  color: var(--jp-ui-font-color2);
}

.jp-InputGroupAction {
  position: absolute;
  bottom: 1px;
  right: 0;
  padding: 6px;
}

.jp-HTMLSelect.jp-DefaultStyle select {
  background-color: initial;
  border: none;
  border-radius: 0;
  box-shadow: none;
  color: var(--jp-ui-font-color0);
  display: block;
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  height: 24px;
  line-height: 14px;
  padding: 0 25px 0 10px;
  text-align: left;
  -moz-appearance: none;
  -webkit-appearance: none;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color2);
  cursor: not-allowed;
  resize: block;
}

.jp-HTMLSelect.jp-DefaultStyle select:disabled ~ span {
  cursor: not-allowed;
}

/* Use our own theme for hover and option styles */
/* stylelint-disable-next-line selector-max-type */
.jp-HTMLSelect.jp-DefaultStyle select:hover,
.jp-HTMLSelect.jp-DefaultStyle select > option {
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color0);
}

select {
  box-sizing: border-box;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-StatusBar-Widget {
  display: flex;
  align-items: center;
  background: var(--jp-layout-color2);
  min-height: var(--jp-statusbar-height);
  justify-content: space-between;
  padding: 0 10px;
}

.jp-StatusBar-Left {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-StatusBar-Middle {
  display: flex;
  align-items: center;
}

.jp-StatusBar-Right {
  display: flex;
  align-items: center;
  flex-direction: row-reverse;
}

.jp-StatusBar-Item {
  max-height: var(--jp-statusbar-height);
  margin: 0 2px;
  height: var(--jp-statusbar-height);
  white-space: nowrap;
  text-overflow: ellipsis;
  color: var(--jp-ui-font-color1);
  padding: 0 6px;
}

.jp-mod-highlighted:hover {
  background-color: var(--jp-layout-color3);
}

.jp-mod-clicked {
  background-color: var(--jp-brand-color1);
}

.jp-mod-clicked:hover {
  background-color: var(--jp-brand-color0);
}

.jp-mod-clicked .jp-StatusBar-TextItem {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-StatusBar-HoverItem {
  box-shadow: '0px 4px 4px rgba(0, 0, 0, 0.25)';
}

.jp-StatusBar-TextItem {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  line-height: 24px;
  color: var(--jp-ui-font-color1);
}

.jp-StatusBar-GroupItem {
  display: flex;
  align-items: center;
  flex-direction: row;
}

.jp-Statusbar-ProgressCircle svg {
  display: block;
  margin: 0 auto;
  width: 16px;
  height: 24px;
  align-self: normal;
}

.jp-Statusbar-ProgressCircle path {
  fill: var(--jp-inverse-layout-color3);
}

.jp-Statusbar-ProgressBar-progress-bar {
  height: 10px;
  width: 100px;
  border: solid 0.25px var(--jp-brand-color2);
  border-radius: 3px;
  overflow: hidden;
  align-self: center;
}

.jp-Statusbar-ProgressBar-progress-bar > div {
  background-color: var(--jp-brand-color2);
  background-image: linear-gradient(
    -45deg,
    rgba(255, 255, 255, 0.2) 25%,
    transparent 25%,
    transparent 50%,
    rgba(255, 255, 255, 0.2) 50%,
    rgba(255, 255, 255, 0.2) 75%,
    transparent 75%,
    transparent
  );
  background-size: 40px 40px;
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 14px;
  color: #fff;
  text-align: center;
  animation: jp-Statusbar-ExecutionTime-progress-bar 2s linear infinite;
}

.jp-Statusbar-ProgressBar-progress-bar p {
  color: var(--jp-ui-font-color1);
  font-family: var(--jp-ui-font-family);
  font-size: var(--jp-ui-font-size1);
  line-height: 10px;
  width: 100px;
}

@keyframes jp-Statusbar-ExecutionTime-progress-bar {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 40px 40px;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-commandpalette-search-height: 28px;
}

/*-----------------------------------------------------------------------------
| Overall styles
|----------------------------------------------------------------------------*/

.lm-CommandPalette {
  padding-bottom: 0;
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Modal variant
|----------------------------------------------------------------------------*/

.jp-ModalCommandPalette {
  position: absolute;
  z-index: 10000;
  top: 38px;
  left: 30%;
  margin: 0;
  padding: 4px;
  width: 40%;
  box-shadow: var(--jp-elevation-z4);
  border-radius: 4px;
  background: var(--jp-layout-color0);
}

.jp-ModalCommandPalette .lm-CommandPalette {
  max-height: 40vh;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-close-icon::after {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-header {
  display: none;
}

.jp-ModalCommandPalette .lm-CommandPalette .lm-CommandPalette-item {
  margin-left: 4px;
  margin-right: 4px;
}

.jp-ModalCommandPalette
  .lm-CommandPalette
  .lm-CommandPalette-item.lm-mod-disabled {
  display: none;
}

/*-----------------------------------------------------------------------------
| Search
|----------------------------------------------------------------------------*/

.lm-CommandPalette-search {
  padding: 4px;
  background-color: var(--jp-layout-color1);
  z-index: 2;
}

.lm-CommandPalette-wrapper {
  overflow: overlay;
  padding: 0 9px;
  background-color: var(--jp-input-active-background);
  height: 30px;
  box-shadow: inset 0 0 0 var(--jp-border-width) var(--jp-input-border-color);
}

.lm-CommandPalette.lm-mod-focused .lm-CommandPalette-wrapper {
  box-shadow: inset 0 0 0 1px var(--jp-input-active-box-shadow-color),
    inset 0 0 0 3px var(--jp-input-active-box-shadow-color);
}

.jp-SearchIconGroup {
  color: white;
  background-color: var(--jp-brand-color1);
  position: absolute;
  top: 4px;
  right: 4px;
  padding: 5px 5px 1px;
}

.jp-SearchIconGroup svg {
  height: 20px;
  width: 20px;
}

.jp-SearchIconGroup .jp-icon3[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-input {
  background: transparent;
  width: calc(100% - 18px);
  float: left;
  border: none;
  outline: none;
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  line-height: var(--jp-private-commandpalette-search-height);
}

.lm-CommandPalette-input::-webkit-input-placeholder,
.lm-CommandPalette-input::-moz-placeholder,
.lm-CommandPalette-input:-ms-input-placeholder {
  color: var(--jp-ui-font-color2);
  font-size: var(--jp-ui-font-size1);
}

/*-----------------------------------------------------------------------------
| Results
|----------------------------------------------------------------------------*/

.lm-CommandPalette-header:first-child {
  margin-top: 0;
}

.lm-CommandPalette-header {
  border-bottom: solid var(--jp-border-width) var(--jp-border-color2);
  color: var(--jp-ui-font-color1);
  cursor: pointer;
  display: flex;
  font-size: var(--jp-ui-font-size0);
  font-weight: 600;
  letter-spacing: 1px;
  margin-top: 8px;
  padding: 8px 0 8px 12px;
  text-transform: uppercase;
}

.lm-CommandPalette-header.lm-mod-active {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-header > mark {
  background-color: transparent;
  font-weight: bold;
  color: var(--jp-ui-font-color1);
}

.lm-CommandPalette-item {
  padding: 4px 12px 4px 4px;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  font-weight: 400;
  display: flex;
}

.lm-CommandPalette-item.lm-mod-disabled {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item.lm-mod-active {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item.lm-mod-active .lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-inverse-font-color0);
}

.lm-CommandPalette-item.lm-mod-active .jp-icon-selectable[fill] {
  fill: var(--jp-layout-color0);
}

.lm-CommandPalette-item.lm-mod-active:hover:not(.lm-mod-disabled) {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.lm-CommandPalette-item:hover:not(.lm-mod-active):not(.lm-mod-disabled) {
  background: var(--jp-layout-color2);
}

.lm-CommandPalette-itemContent {
  overflow: hidden;
}

.lm-CommandPalette-itemLabel > mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.lm-CommandPalette-item.lm-mod-disabled mark {
  color: var(--jp-ui-font-color2);
}

.lm-CommandPalette-item .lm-CommandPalette-itemIcon {
  margin: 0 4px 0 0;
  position: relative;
  width: 16px;
  top: 2px;
  flex: 0 0 auto;
}

.lm-CommandPalette-item.lm-mod-disabled .lm-CommandPalette-itemIcon {
  opacity: 0.6;
}

.lm-CommandPalette-item .lm-CommandPalette-itemShortcut {
  flex: 0 0 auto;
}

.lm-CommandPalette-itemCaption {
  display: none;
}

.lm-CommandPalette-content {
  background-color: var(--jp-layout-color1);
}

.lm-CommandPalette-content:empty::after {
  content: 'No results';
  margin: auto;
  margin-top: 20px;
  width: 100px;
  display: block;
  font-size: var(--jp-ui-font-size2);
  font-family: var(--jp-ui-font-family);
  font-weight: lighter;
}

.lm-CommandPalette-emptyMessage {
  text-align: center;
  margin-top: 24px;
  line-height: 1.32;
  padding: 0 8px;
  color: var(--jp-content-font-color3);
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Dialog {
  position: absolute;
  z-index: 10000;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  top: 0;
  left: 0;
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
  background: var(--jp-dialog-background);
}

.jp-Dialog-content {
  display: flex;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  background: var(--jp-layout-color1);
  padding: 24px 24px 12px;
  min-width: 300px;
  min-height: 150px;
  max-width: 1000px;
  max-height: 500px;
  box-sizing: border-box;
  box-shadow: var(--jp-elevation-z20);
  word-wrap: break-word;
  border-radius: var(--jp-border-radius);

  /* This is needed so that all font sizing of children done in ems is
   * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color1);
  resize: both;
}

.jp-Dialog-content.jp-Dialog-content-small {
  max-width: 500px;
}

.jp-Dialog-button {
  overflow: visible;
}

button.jp-Dialog-button:focus {
  outline: 1px solid var(--jp-brand-color1);
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button:focus::-moz-focus-inner {
  border: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus,
button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline-offset: 4px;
  -moz-outline-radius: 0;
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-accept:focus {
  outline: 1px solid var(--jp-accept-color-normal, var(--jp-brand-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-warn:focus {
  outline: 1px solid var(--jp-warn-color-normal, var(--jp-error-color1));
}

button.jp-Dialog-button.jp-mod-styled.jp-mod-reject:focus {
  outline: 1px solid var(--jp-reject-color-normal, var(--md-grey-600));
}

button.jp-Dialog-close-button {
  padding: 0;
  height: 100%;
  min-width: unset;
  min-height: unset;
}

.jp-Dialog-header {
  display: flex;
  justify-content: space-between;
  flex: 0 0 auto;
  padding-bottom: 12px;
  font-size: var(--jp-ui-font-size3);
  font-weight: 400;
  color: var(--jp-ui-font-color1);
}

.jp-Dialog-body {
  display: flex;
  flex-direction: column;
  flex: 1 1 auto;
  font-size: var(--jp-ui-font-size1);
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  overflow: auto;
}

.jp-Dialog-footer {
  display: flex;
  flex-direction: row;
  justify-content: flex-end;
  align-items: center;
  flex: 0 0 auto;
  margin-left: -12px;
  margin-right: -12px;
  padding: 12px;
}

.jp-Dialog-checkbox {
  padding-right: 5px;
}

.jp-Dialog-checkbox > input:focus-visible {
  outline: 1px solid var(--jp-input-active-border-color);
  outline-offset: 1px;
}

.jp-Dialog-spacer {
  flex: 1 1 auto;
}

.jp-Dialog-title {
  overflow: hidden;
  white-space: nowrap;
  text-overflow: ellipsis;
}

.jp-Dialog-body > .jp-select-wrapper {
  width: 100%;
}

.jp-Dialog-body > button {
  padding: 0 16px;
}

.jp-Dialog-body > label {
  line-height: 1.4;
  color: var(--jp-ui-font-color0);
}

.jp-Dialog-button.jp-mod-styled:not(:last-child) {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Input-Boolean-Dialog {
  flex-direction: row-reverse;
  align-items: end;
  width: 100%;
}

.jp-Input-Boolean-Dialog > label {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MainAreaWidget > :focus {
  outline: none;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error {
  padding: 6px;
}

.jp-MainAreaWidget .jp-MainAreaWidget-error > pre {
  width: auto;
  padding: 10px;
  background: var(--jp-error-color3);
  border: var(--jp-border-width) solid var(--jp-error-color1);
  border-radius: var(--jp-border-radius);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  white-space: pre-wrap;
  word-wrap: break-word;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/**
 * google-material-color v1.2.6
 * https://github.com/danlevan/google-material-color
 */
:root {
  --md-red-50: #ffebee;
  --md-red-100: #ffcdd2;
  --md-red-200: #ef9a9a;
  --md-red-300: #e57373;
  --md-red-400: #ef5350;
  --md-red-500: #f44336;
  --md-red-600: #e53935;
  --md-red-700: #d32f2f;
  --md-red-800: #c62828;
  --md-red-900: #b71c1c;
  --md-red-A100: #ff8a80;
  --md-red-A200: #ff5252;
  --md-red-A400: #ff1744;
  --md-red-A700: #d50000;
  --md-pink-50: #fce4ec;
  --md-pink-100: #f8bbd0;
  --md-pink-200: #f48fb1;
  --md-pink-300: #f06292;
  --md-pink-400: #ec407a;
  --md-pink-500: #e91e63;
  --md-pink-600: #d81b60;
  --md-pink-700: #c2185b;
  --md-pink-800: #ad1457;
  --md-pink-900: #880e4f;
  --md-pink-A100: #ff80ab;
  --md-pink-A200: #ff4081;
  --md-pink-A400: #f50057;
  --md-pink-A700: #c51162;
  --md-purple-50: #f3e5f5;
  --md-purple-100: #e1bee7;
  --md-purple-200: #ce93d8;
  --md-purple-300: #ba68c8;
  --md-purple-400: #ab47bc;
  --md-purple-500: #9c27b0;
  --md-purple-600: #8e24aa;
  --md-purple-700: #7b1fa2;
  --md-purple-800: #6a1b9a;
  --md-purple-900: #4a148c;
  --md-purple-A100: #ea80fc;
  --md-purple-A200: #e040fb;
  --md-purple-A400: #d500f9;
  --md-purple-A700: #a0f;
  --md-deep-purple-50: #ede7f6;
  --md-deep-purple-100: #d1c4e9;
  --md-deep-purple-200: #b39ddb;
  --md-deep-purple-300: #9575cd;
  --md-deep-purple-400: #7e57c2;
  --md-deep-purple-500: #673ab7;
  --md-deep-purple-600: #5e35b1;
  --md-deep-purple-700: #512da8;
  --md-deep-purple-800: #4527a0;
  --md-deep-purple-900: #311b92;
  --md-deep-purple-A100: #b388ff;
  --md-deep-purple-A200: #7c4dff;
  --md-deep-purple-A400: #651fff;
  --md-deep-purple-A700: #6200ea;
  --md-indigo-50: #e8eaf6;
  --md-indigo-100: #c5cae9;
  --md-indigo-200: #9fa8da;
  --md-indigo-300: #7986cb;
  --md-indigo-400: #5c6bc0;
  --md-indigo-500: #3f51b5;
  --md-indigo-600: #3949ab;
  --md-indigo-700: #303f9f;
  --md-indigo-800: #283593;
  --md-indigo-900: #1a237e;
  --md-indigo-A100: #8c9eff;
  --md-indigo-A200: #536dfe;
  --md-indigo-A400: #3d5afe;
  --md-indigo-A700: #304ffe;
  --md-blue-50: #e3f2fd;
  --md-blue-100: #bbdefb;
  --md-blue-200: #90caf9;
  --md-blue-300: #64b5f6;
  --md-blue-400: #42a5f5;
  --md-blue-500: #2196f3;
  --md-blue-600: #1e88e5;
  --md-blue-700: #1976d2;
  --md-blue-800: #1565c0;
  --md-blue-900: #0d47a1;
  --md-blue-A100: #82b1ff;
  --md-blue-A200: #448aff;
  --md-blue-A400: #2979ff;
  --md-blue-A700: #2962ff;
  --md-light-blue-50: #e1f5fe;
  --md-light-blue-100: #b3e5fc;
  --md-light-blue-200: #81d4fa;
  --md-light-blue-300: #4fc3f7;
  --md-light-blue-400: #29b6f6;
  --md-light-blue-500: #03a9f4;
  --md-light-blue-600: #039be5;
  --md-light-blue-700: #0288d1;
  --md-light-blue-800: #0277bd;
  --md-light-blue-900: #01579b;
  --md-light-blue-A100: #80d8ff;
  --md-light-blue-A200: #40c4ff;
  --md-light-blue-A400: #00b0ff;
  --md-light-blue-A700: #0091ea;
  --md-cyan-50: #e0f7fa;
  --md-cyan-100: #b2ebf2;
  --md-cyan-200: #80deea;
  --md-cyan-300: #4dd0e1;
  --md-cyan-400: #26c6da;
  --md-cyan-500: #00bcd4;
  --md-cyan-600: #00acc1;
  --md-cyan-700: #0097a7;
  --md-cyan-800: #00838f;
  --md-cyan-900: #006064;
  --md-cyan-A100: #84ffff;
  --md-cyan-A200: #18ffff;
  --md-cyan-A400: #00e5ff;
  --md-cyan-A700: #00b8d4;
  --md-teal-50: #e0f2f1;
  --md-teal-100: #b2dfdb;
  --md-teal-200: #80cbc4;
  --md-teal-300: #4db6ac;
  --md-teal-400: #26a69a;
  --md-teal-500: #009688;
  --md-teal-600: #00897b;
  --md-teal-700: #00796b;
  --md-teal-800: #00695c;
  --md-teal-900: #004d40;
  --md-teal-A100: #a7ffeb;
  --md-teal-A200: #64ffda;
  --md-teal-A400: #1de9b6;
  --md-teal-A700: #00bfa5;
  --md-green-50: #e8f5e9;
  --md-green-100: #c8e6c9;
  --md-green-200: #a5d6a7;
  --md-green-300: #81c784;
  --md-green-400: #66bb6a;
  --md-green-500: #4caf50;
  --md-green-600: #43a047;
  --md-green-700: #388e3c;
  --md-green-800: #2e7d32;
  --md-green-900: #1b5e20;
  --md-green-A100: #b9f6ca;
  --md-green-A200: #69f0ae;
  --md-green-A400: #00e676;
  --md-green-A700: #00c853;
  --md-light-green-50: #f1f8e9;
  --md-light-green-100: #dcedc8;
  --md-light-green-200: #c5e1a5;
  --md-light-green-300: #aed581;
  --md-light-green-400: #9ccc65;
  --md-light-green-500: #8bc34a;
  --md-light-green-600: #7cb342;
  --md-light-green-700: #689f38;
  --md-light-green-800: #558b2f;
  --md-light-green-900: #33691e;
  --md-light-green-A100: #ccff90;
  --md-light-green-A200: #b2ff59;
  --md-light-green-A400: #76ff03;
  --md-light-green-A700: #64dd17;
  --md-lime-50: #f9fbe7;
  --md-lime-100: #f0f4c3;
  --md-lime-200: #e6ee9c;
  --md-lime-300: #dce775;
  --md-lime-400: #d4e157;
  --md-lime-500: #cddc39;
  --md-lime-600: #c0ca33;
  --md-lime-700: #afb42b;
  --md-lime-800: #9e9d24;
  --md-lime-900: #827717;
  --md-lime-A100: #f4ff81;
  --md-lime-A200: #eeff41;
  --md-lime-A400: #c6ff00;
  --md-lime-A700: #aeea00;
  --md-yellow-50: #fffde7;
  --md-yellow-100: #fff9c4;
  --md-yellow-200: #fff59d;
  --md-yellow-300: #fff176;
  --md-yellow-400: #ffee58;
  --md-yellow-500: #ffeb3b;
  --md-yellow-600: #fdd835;
  --md-yellow-700: #fbc02d;
  --md-yellow-800: #f9a825;
  --md-yellow-900: #f57f17;
  --md-yellow-A100: #ffff8d;
  --md-yellow-A200: #ff0;
  --md-yellow-A400: #ffea00;
  --md-yellow-A700: #ffd600;
  --md-amber-50: #fff8e1;
  --md-amber-100: #ffecb3;
  --md-amber-200: #ffe082;
  --md-amber-300: #ffd54f;
  --md-amber-400: #ffca28;
  --md-amber-500: #ffc107;
  --md-amber-600: #ffb300;
  --md-amber-700: #ffa000;
  --md-amber-800: #ff8f00;
  --md-amber-900: #ff6f00;
  --md-amber-A100: #ffe57f;
  --md-amber-A200: #ffd740;
  --md-amber-A400: #ffc400;
  --md-amber-A700: #ffab00;
  --md-orange-50: #fff3e0;
  --md-orange-100: #ffe0b2;
  --md-orange-200: #ffcc80;
  --md-orange-300: #ffb74d;
  --md-orange-400: #ffa726;
  --md-orange-500: #ff9800;
  --md-orange-600: #fb8c00;
  --md-orange-700: #f57c00;
  --md-orange-800: #ef6c00;
  --md-orange-900: #e65100;
  --md-orange-A100: #ffd180;
  --md-orange-A200: #ffab40;
  --md-orange-A400: #ff9100;
  --md-orange-A700: #ff6d00;
  --md-deep-orange-50: #fbe9e7;
  --md-deep-orange-100: #ffccbc;
  --md-deep-orange-200: #ffab91;
  --md-deep-orange-300: #ff8a65;
  --md-deep-orange-400: #ff7043;
  --md-deep-orange-500: #ff5722;
  --md-deep-orange-600: #f4511e;
  --md-deep-orange-700: #e64a19;
  --md-deep-orange-800: #d84315;
  --md-deep-orange-900: #bf360c;
  --md-deep-orange-A100: #ff9e80;
  --md-deep-orange-A200: #ff6e40;
  --md-deep-orange-A400: #ff3d00;
  --md-deep-orange-A700: #dd2c00;
  --md-brown-50: #efebe9;
  --md-brown-100: #d7ccc8;
  --md-brown-200: #bcaaa4;
  --md-brown-300: #a1887f;
  --md-brown-400: #8d6e63;
  --md-brown-500: #795548;
  --md-brown-600: #6d4c41;
  --md-brown-700: #5d4037;
  --md-brown-800: #4e342e;
  --md-brown-900: #3e2723;
  --md-grey-50: #fafafa;
  --md-grey-100: #f5f5f5;
  --md-grey-200: #eee;
  --md-grey-300: #e0e0e0;
  --md-grey-400: #bdbdbd;
  --md-grey-500: #9e9e9e;
  --md-grey-600: #757575;
  --md-grey-700: #616161;
  --md-grey-800: #424242;
  --md-grey-900: #212121;
  --md-blue-grey-50: #eceff1;
  --md-blue-grey-100: #cfd8dc;
  --md-blue-grey-200: #b0bec5;
  --md-blue-grey-300: #90a4ae;
  --md-blue-grey-400: #78909c;
  --md-blue-grey-500: #607d8b;
  --md-blue-grey-600: #546e7a;
  --md-blue-grey-700: #455a64;
  --md-blue-grey-800: #37474f;
  --md-blue-grey-900: #263238;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2017, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| RenderedText
|----------------------------------------------------------------------------*/

:root {
  /* This is the padding value to fill the gaps between lines containing spans with background color. */
  --jp-private-code-span-padding: calc(
    (var(--jp-code-line-height) - 1) * var(--jp-code-font-size) / 2
  );
}

.jp-RenderedText {
  text-align: left;
  padding-left: var(--jp-code-padding);
  line-height: var(--jp-code-line-height);
  font-family: var(--jp-code-font-family);
}

.jp-RenderedText pre,
.jp-RenderedJavaScript pre,
.jp-RenderedHTMLCommon pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
  border: none;
  margin: 0;
  padding: 0;
}

.jp-RenderedText pre a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedText pre a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* console foregrounds and backgrounds */
.jp-RenderedText pre .ansi-black-fg {
  color: #3e424d;
}

.jp-RenderedText pre .ansi-red-fg {
  color: #e75c58;
}

.jp-RenderedText pre .ansi-green-fg {
  color: #00a250;
}

.jp-RenderedText pre .ansi-yellow-fg {
  color: #ddb62b;
}

.jp-RenderedText pre .ansi-blue-fg {
  color: #208ffb;
}

.jp-RenderedText pre .ansi-magenta-fg {
  color: #d160c4;
}

.jp-RenderedText pre .ansi-cyan-fg {
  color: #60c6c8;
}

.jp-RenderedText pre .ansi-white-fg {
  color: #c5c1b4;
}

.jp-RenderedText pre .ansi-black-bg {
  background-color: #3e424d;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-bg {
  background-color: #e75c58;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-bg {
  background-color: #00a250;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-bg {
  background-color: #ddb62b;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-bg {
  background-color: #208ffb;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-bg {
  background-color: #d160c4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-bg {
  background-color: #60c6c8;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-bg {
  background-color: #c5c1b4;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-black-intense-fg {
  color: #282c36;
}

.jp-RenderedText pre .ansi-red-intense-fg {
  color: #b22b31;
}

.jp-RenderedText pre .ansi-green-intense-fg {
  color: #007427;
}

.jp-RenderedText pre .ansi-yellow-intense-fg {
  color: #b27d12;
}

.jp-RenderedText pre .ansi-blue-intense-fg {
  color: #0065ca;
}

.jp-RenderedText pre .ansi-magenta-intense-fg {
  color: #a03196;
}

.jp-RenderedText pre .ansi-cyan-intense-fg {
  color: #258f8f;
}

.jp-RenderedText pre .ansi-white-intense-fg {
  color: #a1a6b2;
}

.jp-RenderedText pre .ansi-black-intense-bg {
  background-color: #282c36;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-red-intense-bg {
  background-color: #b22b31;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-green-intense-bg {
  background-color: #007427;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-yellow-intense-bg {
  background-color: #b27d12;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-blue-intense-bg {
  background-color: #0065ca;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-magenta-intense-bg {
  background-color: #a03196;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-cyan-intense-bg {
  background-color: #258f8f;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-white-intense-bg {
  background-color: #a1a6b2;
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-default-inverse-fg {
  color: var(--jp-ui-inverse-font-color0);
}

.jp-RenderedText pre .ansi-default-inverse-bg {
  background-color: var(--jp-inverse-layout-color0);
  padding: var(--jp-private-code-span-padding) 0;
}

.jp-RenderedText pre .ansi-bold {
  font-weight: bold;
}

.jp-RenderedText pre .ansi-underline {
  text-decoration: underline;
}

.jp-RenderedText[data-mime-type='application/vnd.jupyter.stderr'] {
  background: var(--jp-rendermime-error-background);
  padding-top: var(--jp-code-padding);
}

/*-----------------------------------------------------------------------------
| RenderedLatex
|----------------------------------------------------------------------------*/

.jp-RenderedLatex {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);
}

/* Left-justify outputs.*/
.jp-OutputArea-output.jp-RenderedLatex {
  padding: var(--jp-code-padding);
  text-align: left;
}

/*-----------------------------------------------------------------------------
| RenderedHTML
|----------------------------------------------------------------------------*/

.jp-RenderedHTMLCommon {
  color: var(--jp-content-font-color1);
  font-family: var(--jp-content-font-family);
  font-size: var(--jp-content-font-size1);
  line-height: var(--jp-content-line-height);

  /* Give a bit more R padding on Markdown text to keep line lengths reasonable */
  padding-right: 20px;
}

.jp-RenderedHTMLCommon em {
  font-style: italic;
}

.jp-RenderedHTMLCommon strong {
  font-weight: bold;
}

.jp-RenderedHTMLCommon u {
  text-decoration: underline;
}

.jp-RenderedHTMLCommon a:link {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:hover {
  text-decoration: underline;
  color: var(--jp-content-link-color);
}

.jp-RenderedHTMLCommon a:visited {
  text-decoration: none;
  color: var(--jp-content-link-color);
}

/* Headings */

.jp-RenderedHTMLCommon h1,
.jp-RenderedHTMLCommon h2,
.jp-RenderedHTMLCommon h3,
.jp-RenderedHTMLCommon h4,
.jp-RenderedHTMLCommon h5,
.jp-RenderedHTMLCommon h6 {
  line-height: var(--jp-content-heading-line-height);
  font-weight: var(--jp-content-heading-font-weight);
  font-style: normal;
  margin: var(--jp-content-heading-margin-top) 0
    var(--jp-content-heading-margin-bottom) 0;
}

.jp-RenderedHTMLCommon h1:first-child,
.jp-RenderedHTMLCommon h2:first-child,
.jp-RenderedHTMLCommon h3:first-child,
.jp-RenderedHTMLCommon h4:first-child,
.jp-RenderedHTMLCommon h5:first-child,
.jp-RenderedHTMLCommon h6:first-child {
  margin-top: calc(0.5 * var(--jp-content-heading-margin-top));
}

.jp-RenderedHTMLCommon h1:last-child,
.jp-RenderedHTMLCommon h2:last-child,
.jp-RenderedHTMLCommon h3:last-child,
.jp-RenderedHTMLCommon h4:last-child,
.jp-RenderedHTMLCommon h5:last-child,
.jp-RenderedHTMLCommon h6:last-child {
  margin-bottom: calc(0.5 * var(--jp-content-heading-margin-bottom));
}

.jp-RenderedHTMLCommon h1 {
  font-size: var(--jp-content-font-size5);
}

.jp-RenderedHTMLCommon h2 {
  font-size: var(--jp-content-font-size4);
}

.jp-RenderedHTMLCommon h3 {
  font-size: var(--jp-content-font-size3);
}

.jp-RenderedHTMLCommon h4 {
  font-size: var(--jp-content-font-size2);
}

.jp-RenderedHTMLCommon h5 {
  font-size: var(--jp-content-font-size1);
}

.jp-RenderedHTMLCommon h6 {
  font-size: var(--jp-content-font-size0);
}

/* Lists */

/* stylelint-disable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon ul:not(.list-inline),
.jp-RenderedHTMLCommon ol:not(.list-inline) {
  padding-left: 2em;
}

.jp-RenderedHTMLCommon ul {
  list-style: disc;
}

.jp-RenderedHTMLCommon ul ul {
  list-style: square;
}

.jp-RenderedHTMLCommon ul ul ul {
  list-style: circle;
}

.jp-RenderedHTMLCommon ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol ol {
  list-style: upper-alpha;
}

.jp-RenderedHTMLCommon ol ol ol {
  list-style: lower-alpha;
}

.jp-RenderedHTMLCommon ol ol ol ol {
  list-style: lower-roman;
}

.jp-RenderedHTMLCommon ol ol ol ol ol {
  list-style: decimal;
}

.jp-RenderedHTMLCommon ol,
.jp-RenderedHTMLCommon ul {
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon ul ul,
.jp-RenderedHTMLCommon ul ol,
.jp-RenderedHTMLCommon ol ul,
.jp-RenderedHTMLCommon ol ol {
  margin-bottom: 0;
}

/* stylelint-enable selector-max-type, selector-max-compound-selectors */

.jp-RenderedHTMLCommon hr {
  color: var(--jp-border-color2);
  background-color: var(--jp-border-color1);
  margin-top: 1em;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon > pre {
  margin: 1.5em 2em;
}

.jp-RenderedHTMLCommon pre,
.jp-RenderedHTMLCommon code {
  border: 0;
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  line-height: var(--jp-code-line-height);
  padding: 0;
  white-space: pre-wrap;
}

.jp-RenderedHTMLCommon :not(pre) > code {
  background-color: var(--jp-layout-color2);
  padding: 1px 5px;
}

/* Tables */

.jp-RenderedHTMLCommon table {
  border-collapse: collapse;
  border-spacing: 0;
  border: none;
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  table-layout: fixed;
  margin-left: auto;
  margin-bottom: 1em;
  margin-right: auto;
}

.jp-RenderedHTMLCommon thead {
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  vertical-align: bottom;
}

.jp-RenderedHTMLCommon td,
.jp-RenderedHTMLCommon th,
.jp-RenderedHTMLCommon tr {
  vertical-align: middle;
  padding: 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}

.jp-RenderedMarkdown.jp-RenderedHTMLCommon td,
.jp-RenderedMarkdown.jp-RenderedHTMLCommon th {
  max-width: none;
}

:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon td,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon th,
:not(.jp-RenderedMarkdown).jp-RenderedHTMLCommon tr {
  text-align: right;
}

.jp-RenderedHTMLCommon th {
  font-weight: bold;
}

.jp-RenderedHTMLCommon tbody tr:nth-child(odd) {
  background: var(--jp-layout-color0);
}

.jp-RenderedHTMLCommon tbody tr:nth-child(even) {
  background: var(--jp-rendermime-table-row-background);
}

.jp-RenderedHTMLCommon tbody tr:hover {
  background: var(--jp-rendermime-table-row-hover-background);
}

.jp-RenderedHTMLCommon p {
  text-align: left;
  margin: 0;
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon img {
  -moz-force-broken-image-icon: 1;
}

/* Restrict to direct children as other images could be nested in other content. */
.jp-RenderedHTMLCommon > img {
  display: block;
  margin-left: 0;
  margin-right: 0;
  margin-bottom: 1em;
}

/* Change color behind transparent images if they need it... */
[data-jp-theme-light='false'] .jp-RenderedImage img.jp-needs-light-background {
  background-color: var(--jp-inverse-layout-color1);
}

[data-jp-theme-light='true'] .jp-RenderedImage img.jp-needs-dark-background {
  background-color: var(--jp-inverse-layout-color1);
}

.jp-RenderedHTMLCommon img,
.jp-RenderedImage img,
.jp-RenderedHTMLCommon svg,
.jp-RenderedSVG svg {
  max-width: 100%;
  height: auto;
}

.jp-RenderedHTMLCommon img.jp-mod-unconfined,
.jp-RenderedImage img.jp-mod-unconfined,
.jp-RenderedHTMLCommon svg.jp-mod-unconfined,
.jp-RenderedSVG svg.jp-mod-unconfined {
  max-width: none;
}

.jp-RenderedHTMLCommon .alert {
  padding: var(--jp-notebook-padding);
  border: var(--jp-border-width) solid transparent;
  border-radius: var(--jp-border-radius);
  margin-bottom: 1em;
}

.jp-RenderedHTMLCommon .alert-info {
  color: var(--jp-info-color0);
  background-color: var(--jp-info-color3);
  border-color: var(--jp-info-color2);
}

.jp-RenderedHTMLCommon .alert-info hr {
  border-color: var(--jp-info-color3);
}

.jp-RenderedHTMLCommon .alert-info > p:last-child,
.jp-RenderedHTMLCommon .alert-info > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-warning {
  color: var(--jp-warn-color0);
  background-color: var(--jp-warn-color3);
  border-color: var(--jp-warn-color2);
}

.jp-RenderedHTMLCommon .alert-warning hr {
  border-color: var(--jp-warn-color3);
}

.jp-RenderedHTMLCommon .alert-warning > p:last-child,
.jp-RenderedHTMLCommon .alert-warning > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-success {
  color: var(--jp-success-color0);
  background-color: var(--jp-success-color3);
  border-color: var(--jp-success-color2);
}

.jp-RenderedHTMLCommon .alert-success hr {
  border-color: var(--jp-success-color3);
}

.jp-RenderedHTMLCommon .alert-success > p:last-child,
.jp-RenderedHTMLCommon .alert-success > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon .alert-danger {
  color: var(--jp-error-color0);
  background-color: var(--jp-error-color3);
  border-color: var(--jp-error-color2);
}

.jp-RenderedHTMLCommon .alert-danger hr {
  border-color: var(--jp-error-color3);
}

.jp-RenderedHTMLCommon .alert-danger > p:last-child,
.jp-RenderedHTMLCommon .alert-danger > ul:last-child {
  margin-bottom: 0;
}

.jp-RenderedHTMLCommon blockquote {
  margin: 1em 2em;
  padding: 0 1em;
  border-left: 5px solid var(--jp-border-color2);
}

a.jp-InternalAnchorLink {
  visibility: hidden;
  margin-left: 8px;
  color: var(--md-blue-800);
}

h1:hover .jp-InternalAnchorLink,
h2:hover .jp-InternalAnchorLink,
h3:hover .jp-InternalAnchorLink,
h4:hover .jp-InternalAnchorLink,
h5:hover .jp-InternalAnchorLink,
h6:hover .jp-InternalAnchorLink {
  visibility: visible;
}

.jp-RenderedHTMLCommon kbd {
  background-color: var(--jp-rendermime-table-row-background);
  border: 1px solid var(--jp-border-color0);
  border-bottom-color: var(--jp-border-color2);
  border-radius: 3px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
  display: inline-block;
  font-size: var(--jp-ui-font-size0);
  line-height: 1em;
  padding: 0.2em 0.5em;
}

/* Most direct children of .jp-RenderedHTMLCommon have a margin-bottom of 1.0.
 * At the bottom of cells this is a bit too much as there is also spacing
 * between cells. Going all the way to 0 gets too tight between markdown and
 * code cells.
 */
.jp-RenderedHTMLCommon > *:last-child {
  margin-bottom: 0.5em;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Copyright (c) 2014-2017, PhosphorJS Contributors
|
| Distributed under the terms of the BSD 3-Clause License.
|
| The full license is in the file LICENSE, distributed with this software.
|----------------------------------------------------------------------------*/

.lm-cursor-backdrop {
  position: fixed;
  width: 200px;
  height: 200px;
  margin-top: -100px;
  margin-left: -100px;
  will-change: transform;
  z-index: 100;
}

.lm-mod-drag-image {
  will-change: transform;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-lineFormSearch {
  padding: 4px 12px;
  background-color: var(--jp-layout-color2);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
  font-size: var(--jp-ui-font-size1);
}

.jp-lineFormCaption {
  font-size: var(--jp-ui-font-size0);
  line-height: var(--jp-ui-font-size1);
  margin-top: 4px;
  color: var(--jp-ui-font-color0);
}

.jp-baseLineForm {
  border: none;
  border-radius: 0;
  position: absolute;
  background-size: 16px;
  background-repeat: no-repeat;
  background-position: center;
  outline: none;
}

.jp-lineFormButtonContainer {
  top: 4px;
  right: 8px;
  height: 24px;
  padding: 0 12px;
  width: 12px;
}

.jp-lineFormButtonIcon {
  top: 0;
  right: 0;
  background-color: var(--jp-brand-color1);
  height: 100%;
  width: 100%;
  box-sizing: border-box;
  padding: 4px 6px;
}

.jp-lineFormButton {
  top: 0;
  right: 0;
  background-color: transparent;
  height: 100%;
  width: 100%;
  box-sizing: border-box;
}

.jp-lineFormWrapper {
  overflow: hidden;
  padding: 0 8px;
  border: 1px solid var(--jp-border-color0);
  background-color: var(--jp-input-active-background);
  height: 22px;
}

.jp-lineFormWrapperFocusWithin {
  border: var(--jp-border-width) solid var(--md-blue-500);
  box-shadow: inset 0 0 4px var(--md-blue-300);
}

.jp-lineFormInput {
  background: transparent;
  width: 200px;
  height: 100%;
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  line-height: 28px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) 2014-2016, Jupyter Development Team.
|
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-JSONEditor {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.jp-JSONEditor-host {
  flex: 1 1 auto;
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  border-radius: 0;
  background: var(--jp-layout-color0);
  min-height: 50px;
  padding: 1px;
}

.jp-JSONEditor.jp-mod-error .jp-JSONEditor-host {
  border-color: red;
  outline-color: red;
}

.jp-JSONEditor-header {
  display: flex;
  flex: 1 0 auto;
  padding: 0 0 0 12px;
}

.jp-JSONEditor-header label {
  flex: 0 0 auto;
}

.jp-JSONEditor-commitButton {
  height: 16px;
  width: 16px;
  background-size: 18px;
  background-repeat: no-repeat;
  background-position: center;
}

.jp-JSONEditor-host.jp-mod-focused {
  background-color: var(--jp-input-active-background);
  border: 1px solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

.jp-Editor.jp-mod-dropTarget {
  border: var(--jp-border-width) solid var(--jp-input-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/
.jp-DocumentSearch-input {
  border: none;
  outline: none;
  color: var(--jp-ui-font-color0);
  font-size: var(--jp-ui-font-size1);
  background-color: var(--jp-layout-color0);
  font-family: var(--jp-ui-font-family);
  padding: 2px 1px;
  resize: none;
}

.jp-DocumentSearch-overlay {
  position: absolute;
  background-color: var(--jp-toolbar-background);
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  border-left: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  top: 0;
  right: 0;
  z-index: 7;
  min-width: 405px;
  padding: 2px;
  font-size: var(--jp-ui-font-size1);

  --jp-private-document-search-button-height: 20px;
}

.jp-DocumentSearch-overlay button {
  background-color: var(--jp-toolbar-background);
  outline: 0;
}

.jp-DocumentSearch-overlay button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-overlay button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-overlay-row {
  display: flex;
  align-items: center;
  margin-bottom: 2px;
}

.jp-DocumentSearch-button-content {
  display: inline-block;
  cursor: pointer;
  box-sizing: border-box;
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-button-content svg {
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-input-wrapper {
  border: var(--jp-border-width) solid var(--jp-border-color0);
  display: flex;
  background-color: var(--jp-layout-color0);
  margin: 2px;
}

.jp-DocumentSearch-input-wrapper:focus-within {
  border-color: var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper {
  all: initial;
  overflow: hidden;
  display: inline-block;
  border: none;
  box-sizing: border-box;
}

.jp-DocumentSearch-toggle-wrapper {
  width: 14px;
  height: 14px;
}

.jp-DocumentSearch-button-wrapper {
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
}

.jp-DocumentSearch-toggle-wrapper:focus,
.jp-DocumentSearch-button-wrapper:focus {
  outline: var(--jp-border-width) solid
    var(--jp-cell-editor-active-border-color);
  outline-offset: -1px;
}

.jp-DocumentSearch-toggle-wrapper,
.jp-DocumentSearch-button-wrapper,
.jp-DocumentSearch-button-content:focus {
  outline: none;
}

.jp-DocumentSearch-toggle-placeholder {
  width: 5px;
}

.jp-DocumentSearch-input-button::before {
  display: block;
  padding-top: 100%;
}

.jp-DocumentSearch-input-button-off {
  opacity: var(--jp-search-toggle-off-opacity);
}

.jp-DocumentSearch-input-button-off:hover {
  opacity: var(--jp-search-toggle-hover-opacity);
}

.jp-DocumentSearch-input-button-on {
  opacity: var(--jp-search-toggle-on-opacity);
}

.jp-DocumentSearch-index-counter {
  padding-left: 10px;
  padding-right: 10px;
  user-select: none;
  min-width: 35px;
  display: inline-block;
}

.jp-DocumentSearch-up-down-wrapper {
  display: inline-block;
  padding-right: 2px;
  margin-left: auto;
  white-space: nowrap;
}

.jp-DocumentSearch-spacer {
  margin-left: auto;
}

.jp-DocumentSearch-up-down-wrapper button {
  outline: 0;
  border: none;
  width: var(--jp-private-document-search-button-height);
  height: var(--jp-private-document-search-button-height);
  vertical-align: middle;
  margin: 1px 5px 2px;
}

.jp-DocumentSearch-up-down-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-up-down-button:active {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-filter-button {
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-filter-button:hover {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled {
  background-color: var(--jp-layout-color2);
}

.jp-DocumentSearch-filter-button-enabled:hover {
  background-color: var(--jp-layout-color3);
}

.jp-DocumentSearch-search-options {
  padding: 0 8px;
  margin-left: 3px;
  width: 100%;
  display: grid;
  justify-content: start;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  justify-items: stretch;
}

.jp-DocumentSearch-search-filter-disabled {
  color: var(--jp-ui-font-color2);
}

.jp-DocumentSearch-search-filter {
  display: flex;
  align-items: center;
  user-select: none;
}

.jp-DocumentSearch-regex-error {
  color: var(--jp-error-color0);
}

.jp-DocumentSearch-replace-button-wrapper {
  overflow: hidden;
  display: inline-block;
  box-sizing: border-box;
  border: var(--jp-border-width) solid var(--jp-border-color0);
  margin: auto 2px;
  padding: 1px 4px;
  height: calc(var(--jp-private-document-search-button-height) + 2px);
}

.jp-DocumentSearch-replace-button-wrapper:focus {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
}

.jp-DocumentSearch-replace-button {
  display: inline-block;
  text-align: center;
  cursor: pointer;
  box-sizing: border-box;
  color: var(--jp-ui-font-color1);

  /* height - 2 * (padding of wrapper) */
  line-height: calc(var(--jp-private-document-search-button-height) - 2px);
  width: 100%;
  height: 100%;
}

.jp-DocumentSearch-replace-button:focus {
  outline: none;
}

.jp-DocumentSearch-replace-wrapper-class {
  margin-left: 14px;
  display: flex;
}

.jp-DocumentSearch-replace-toggle {
  border: none;
  background-color: var(--jp-toolbar-background);
  border-radius: var(--jp-border-radius);
}

.jp-DocumentSearch-replace-toggle:hover {
  background-color: var(--jp-layout-color2);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.cm-editor {
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  border: 0;
  border-radius: 0;
  height: auto;

  /* Changed to auto to autogrow */
}

.cm-editor pre {
  padding: 0 var(--jp-code-padding);
}

.jp-CodeMirrorEditor[data-type='inline'] .cm-dialog {
  background-color: var(--jp-layout-color0);
  color: var(--jp-content-font-color1);
}

.jp-CodeMirrorEditor {
  cursor: text;
}

/* When zoomed out 67% and 33% on a screen of 1440 width x 900 height */
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width1) solid
      var(--jp-editor-cursor-color);
  }
}

/* When zoomed out less than 33% */
@media screen and (min-width: 4320px) {
  .jp-CodeMirrorEditor[data-type='inline'] .cm-cursor {
    border-left: var(--jp-code-cursor-width2) solid
      var(--jp-editor-cursor-color);
  }
}

.cm-editor.jp-mod-readOnly .cm-cursor {
  display: none;
}

.jp-CollaboratorCursor {
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-top: none;
  border-bottom: 3px solid;
  background-clip: content-box;
  margin-left: -5px;
  margin-right: -5px;
}

.cm-searching,
.cm-searching span {
  /* `.cm-searching span`: we need to override syntax highlighting */
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.cm-searching::selection,
.cm-searching span::selection {
  background-color: var(--jp-search-unselected-match-background-color);
  color: var(--jp-search-unselected-match-color);
}

.jp-current-match > .cm-searching,
.jp-current-match > .cm-searching span,
.cm-searching > .jp-current-match,
.cm-searching > .jp-current-match span {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.jp-current-match > .cm-searching::selection,
.cm-searching > .jp-current-match::selection,
.jp-current-match > .cm-searching span::selection {
  background-color: var(--jp-search-selected-match-background-color);
  color: var(--jp-search-selected-match-color);
}

.cm-trailingspace {
  background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAgAAAAFCAYAAAB4ka1VAAAAsElEQVQIHQGlAFr/AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA7+r3zKmT0/+pk9P/7+r3zAAAAAAAAAAABAAAAAAAAAAA6OPzM+/q9wAAAAAA6OPzMwAAAAAAAAAAAgAAAAAAAAAAGR8NiRQaCgAZIA0AGR8NiQAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQyoYJ/SY80UAAAAASUVORK5CYII=);
  background-position: center left;
  background-repeat: repeat-x;
}

.jp-CollaboratorCursor-hover {
  position: absolute;
  z-index: 1;
  transform: translateX(-50%);
  color: white;
  border-radius: 3px;
  padding-left: 4px;
  padding-right: 4px;
  padding-top: 1px;
  padding-bottom: 1px;
  text-align: center;
  font-size: var(--jp-ui-font-size1);
  white-space: nowrap;
}

.jp-CodeMirror-ruler {
  border-left: 1px dashed var(--jp-border-color2);
}

/* Styles for shared cursors (remote cursor locations and selected ranges) */
.jp-CodeMirrorEditor .cm-ySelectionCaret {
  position: relative;
  border-left: 1px solid black;
  margin-left: -1px;
  margin-right: -1px;
  box-sizing: border-box;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret > .cm-ySelectionInfo {
  white-space: nowrap;
  position: absolute;
  top: -1.15em;
  padding-bottom: 0.05em;
  left: -1px;
  font-size: 0.95em;
  font-family: var(--jp-ui-font-family);
  font-weight: bold;
  line-height: normal;
  user-select: none;
  color: white;
  padding-left: 2px;
  padding-right: 2px;
  z-index: 101;
  transition: opacity 0.3s ease-in-out;
}

.jp-CodeMirrorEditor .cm-ySelectionInfo {
  transition-delay: 0.7s;
  opacity: 0;
}

.jp-CodeMirrorEditor .cm-ySelectionCaret:hover > .cm-ySelectionInfo {
  opacity: 1;
  transition-delay: 0s;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-MimeDocument {
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-filebrowser-button-height: 28px;
  --jp-private-filebrowser-button-width: 48px;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-FileBrowser .jp-SidePanel-content {
  display: flex;
  flex-direction: column;
}

.jp-FileBrowser-toolbar.jp-Toolbar {
  flex-wrap: wrap;
  row-gap: 12px;
  border-bottom: none;
  height: auto;
  margin: 8px 12px 0;
  box-shadow: none;
  padding: 0;
  justify-content: flex-start;
}

.jp-FileBrowser-Panel {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
}

.jp-BreadCrumbs {
  flex: 0 0 auto;
  margin: 8px 12px;
}

.jp-BreadCrumbs-item {
  margin: 0 2px;
  padding: 0 2px;
  border-radius: var(--jp-border-radius);
  cursor: pointer;
}

.jp-BreadCrumbs-item:hover {
  background-color: var(--jp-layout-color2);
}

.jp-BreadCrumbs-item:first-child {
  margin-left: 0;
}

.jp-BreadCrumbs-item.jp-mod-dropTarget {
  background-color: var(--jp-brand-color2);
  opacity: 0.7;
}

/*-----------------------------------------------------------------------------
| Buttons
|----------------------------------------------------------------------------*/

.jp-FileBrowser-toolbar > .jp-Toolbar-item {
  flex: 0 0 auto;
  padding-left: 0;
  padding-right: 2px;
  align-items: center;
  height: unset;
}

.jp-FileBrowser-toolbar > .jp-Toolbar-item .jp-ToolbarButtonComponent {
  width: 40px;
}

/*-----------------------------------------------------------------------------
| Other styles
|----------------------------------------------------------------------------*/

.jp-FileDialog.jp-mod-conflict input {
  color: var(--jp-error-color1);
}

.jp-FileDialog .jp-new-name-title {
  margin-top: 12px;
}

.jp-LastModified-hidden {
  display: none;
}

.jp-FileSize-hidden {
  display: none;
}

.jp-FileBrowser .lm-AccordionPanel > h3:first-child {
  display: none;
}

/*-----------------------------------------------------------------------------
| DirListing
|----------------------------------------------------------------------------*/

.jp-DirListing {
  flex: 1 1 auto;
  display: flex;
  flex-direction: column;
  outline: 0;
}

.jp-DirListing-header {
  flex: 0 0 auto;
  display: flex;
  flex-direction: row;
  align-items: center;
  overflow: hidden;
  border-top: var(--jp-border-width) solid var(--jp-border-color2);
  border-bottom: var(--jp-border-width) solid var(--jp-border-color1);
  box-shadow: var(--jp-toolbar-box-shadow);
  z-index: 2;
}

.jp-DirListing-headerItem {
  padding: 4px 12px 2px;
  font-weight: 500;
}

.jp-DirListing-headerItem:hover {
  background: var(--jp-layout-color2);
}

.jp-DirListing-headerItem.jp-id-name {
  flex: 1 0 84px;
}

.jp-DirListing-headerItem.jp-id-modified {
  flex: 0 0 112px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-DirListing-headerItem.jp-id-filesize {
  flex: 0 0 75px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
}

.jp-id-narrow {
  display: none;
  flex: 0 0 5px;
  padding: 4px;
  border-left: var(--jp-border-width) solid var(--jp-border-color2);
  text-align: right;
  color: var(--jp-border-color2);
}

.jp-DirListing-narrow .jp-id-narrow {
  display: block;
}

.jp-DirListing-narrow .jp-id-modified,
.jp-DirListing-narrow .jp-DirListing-itemModified {
  display: none;
}

.jp-DirListing-headerItem.jp-mod-selected {
  font-weight: 600;
}

/* increase specificity to override bundled default */
.jp-DirListing-content {
  flex: 1 1 auto;
  margin: 0;
  padding: 0;
  list-style-type: none;
  overflow: auto;
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-content mark {
  color: var(--jp-ui-font-color0);
  background-color: transparent;
  font-weight: bold;
}

.jp-DirListing-content .jp-DirListing-item.jp-mod-selected mark {
  color: var(--jp-ui-inverse-font-color0);
}

/* Style the directory listing content when a user drops a file to upload */
.jp-DirListing.jp-mod-native-drop .jp-DirListing-content {
  outline: 5px dashed rgba(128, 128, 128, 0.5);
  outline-offset: -10px;
  cursor: copy;
}

.jp-DirListing-item {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 4px 12px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-DirListing-checkboxWrapper {
  /* Increases hit area of checkbox. */
  padding: 4px;
}

.jp-DirListing-header
  .jp-DirListing-checkboxWrapper
  + .jp-DirListing-headerItem {
  padding-left: 4px;
}

.jp-DirListing-content .jp-DirListing-checkboxWrapper {
  position: relative;
  left: -4px;
  margin: -4px 0 -4px -8px;
}

.jp-DirListing-checkboxWrapper.jp-mod-visible {
  visibility: visible;
}

/* For devices that support hovering, hide checkboxes until hovered, selected...
*/
@media (hover: hover) {
  .jp-DirListing-checkboxWrapper {
    visibility: hidden;
  }

  .jp-DirListing-item:hover .jp-DirListing-checkboxWrapper,
  .jp-DirListing-item.jp-mod-selected .jp-DirListing-checkboxWrapper {
    visibility: visible;
  }
}

.jp-DirListing-item[data-is-dot] {
  opacity: 75%;
}

.jp-DirListing-item.jp-mod-selected {
  color: var(--jp-ui-inverse-font-color1);
  background: var(--jp-brand-color1);
}

.jp-DirListing-item.jp-mod-dropTarget {
  background: var(--jp-brand-color3);
}

.jp-DirListing-item:hover:not(.jp-mod-selected) {
  background: var(--jp-layout-color2);
}

.jp-DirListing-itemIcon {
  flex: 0 0 20px;
  margin-right: 4px;
}

.jp-DirListing-itemText {
  flex: 1 0 64px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  user-select: none;
}

.jp-DirListing-itemText:focus {
  outline-width: 2px;
  outline-color: var(--jp-inverse-layout-color1);
  outline-style: solid;
  outline-offset: 1px;
}

.jp-DirListing-item.jp-mod-selected .jp-DirListing-itemText:focus {
  outline-color: var(--jp-layout-color1);
}

.jp-DirListing-itemModified {
  flex: 0 0 125px;
  text-align: right;
}

.jp-DirListing-itemFileSize {
  flex: 0 0 90px;
  text-align: right;
}

.jp-DirListing-editor {
  flex: 1 0 64px;
  outline: none;
  border: none;
  color: var(--jp-ui-font-color1);
  background-color: var(--jp-layout-color1);
}

.jp-DirListing-item.jp-mod-running .jp-DirListing-itemIcon::before {
  color: var(--jp-success-color1);
  content: '\25CF';
  font-size: 8px;
  position: absolute;
  left: -8px;
}

.jp-DirListing-item.jp-mod-running.jp-mod-selected
  .jp-DirListing-itemIcon::before {
  color: var(--jp-ui-inverse-font-color1);
}

.jp-DirListing-item.lm-mod-drag-image,
.jp-DirListing-item.jp-mod-selected.lm-mod-drag-image {
  font-size: var(--jp-ui-font-size1);
  padding-left: 4px;
  margin-left: 4px;
  width: 160px;
  background-color: var(--jp-ui-inverse-font-color2);
  box-shadow: var(--jp-elevation-z2);
  border-radius: 0;
  color: var(--jp-ui-font-color1);
  transform: translateX(-40%) translateY(-58%);
}

.jp-Document {
  min-width: 120px;
  min-height: 120px;
  outline: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Main OutputArea
| OutputArea has a list of Outputs
|----------------------------------------------------------------------------*/

.jp-OutputArea {
  overflow-y: auto;
}

.jp-OutputArea-child {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-OutputPrompt {
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-outprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
  opacity: var(--jp-cell-prompt-opacity);

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-OutputArea-prompt {
  display: table-cell;
  vertical-align: top;
}

.jp-OutputArea-output {
  display: table-cell;
  width: 100%;
  height: auto;
  overflow: auto;
  user-select: text;
  -moz-user-select: text;
  -webkit-user-select: text;
  -ms-user-select: text;
}

.jp-OutputArea .jp-RenderedText {
  padding-left: 1ch;
}

/**
 * Prompt overlay.
 */

.jp-OutputArea-promptOverlay {
  position: absolute;
  top: 0;
  width: var(--jp-cell-prompt-width);
  height: 100%;
  opacity: 0.5;
}

.jp-OutputArea-promptOverlay:hover {
  background: var(--jp-layout-color2);
  box-shadow: inset 0 0 1px var(--jp-inverse-layout-color0);
  cursor: zoom-out;
}

.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay:hover {
  cursor: zoom-in;
}

/**
 * Isolated output.
 */
.jp-OutputArea-output.jp-mod-isolated {
  width: 100%;
  display: block;
}

/*
When drag events occur, `lm-mod-override-cursor` is added to the body.
Because iframes steal all cursor events, the following two rules are necessary
to suppress pointer events while resize drags are occurring. There may be a
better solution to this problem.
*/
body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated {
  position: relative;
}

body.lm-mod-override-cursor .jp-OutputArea-output.jp-mod-isolated::before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: transparent;
}

/* pre */

.jp-OutputArea-output pre {
  border: none;
  margin: 0;
  padding: 0;
  overflow-x: auto;
  overflow-y: auto;
  word-break: break-all;
  word-wrap: break-word;
  white-space: pre-wrap;
}

/* tables */

.jp-OutputArea-output.jp-RenderedHTMLCommon table {
  margin-left: 0;
  margin-right: 0;
}

/* description lists */

.jp-OutputArea-output dl,
.jp-OutputArea-output dt,
.jp-OutputArea-output dd {
  display: block;
}

.jp-OutputArea-output dl {
  width: 100%;
  overflow: hidden;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dt {
  font-weight: bold;
  float: left;
  width: 20%;
  padding: 0;
  margin: 0;
}

.jp-OutputArea-output dd {
  float: left;
  width: 80%;
  padding: 0;
  margin: 0;
}

.jp-TrimmedOutputs pre {
  background: var(--jp-layout-color3);
  font-size: calc(var(--jp-code-font-size) * 1.4);
  text-align: center;
  text-transform: uppercase;
}

/* Hide the gutter in case of
 *  - nested output areas (e.g. in the case of output widgets)
 *  - mirrored output areas
 */
.jp-OutputArea .jp-OutputArea .jp-OutputArea-prompt {
  display: none;
}

/* Hide empty lines in the output area, for instance due to cleared widgets */
.jp-OutputArea-prompt:empty {
  padding: 0;
  border: 0;
}

/*-----------------------------------------------------------------------------
| executeResult is added to any Output-result for the display of the object
| returned by a cell
|----------------------------------------------------------------------------*/

.jp-OutputArea-output.jp-OutputArea-executeResult {
  margin-left: 0;
  width: 100%;
}

/* Text output with the Out[] prompt needs a top padding to match the
 * alignment of the Out[] prompt itself.
 */
.jp-OutputArea-executeResult .jp-RenderedText.jp-OutputArea-output {
  padding-top: var(--jp-code-padding);
  border-top: var(--jp-border-width) solid transparent;
}

/*-----------------------------------------------------------------------------
| The Stdin output
|----------------------------------------------------------------------------*/

.jp-Stdin-prompt {
  color: var(--jp-content-font-color0);
  padding-right: var(--jp-code-padding);
  vertical-align: baseline;
  flex: 0 0 auto;
}

.jp-Stdin-input {
  font-family: var(--jp-code-font-family);
  font-size: inherit;
  color: inherit;
  background-color: inherit;
  width: 42%;
  min-width: 200px;

  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;

  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0 0.25em;
  margin: 0 0.25em;
  flex: 0 0 70%;
}

.jp-Stdin-input::placeholder {
  opacity: 0;
}

.jp-Stdin-input:focus {
  box-shadow: none;
}

.jp-Stdin-input:focus::placeholder {
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Output Area View
|----------------------------------------------------------------------------*/

.jp-LinkedOutputView .jp-OutputArea {
  height: 100%;
  display: block;
}

.jp-LinkedOutputView .jp-OutputArea-output:only-child {
  height: 100%;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

@media print {
  .jp-OutputArea-child {
    break-inside: avoid-page;
  }
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-OutputPrompt {
    display: table-row;
    text-align: left;
  }

  .jp-OutputArea-child .jp-OutputArea-output {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }
}

/* Trimmed outputs warning */
.jp-TrimmedOutputs > a {
  margin: 10px;
  text-decoration: none;
  cursor: pointer;
}

.jp-TrimmedOutputs > a:hover {
  text-decoration: none;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Table of Contents
|----------------------------------------------------------------------------*/

:root {
  --jp-private-toc-active-width: 4px;
}

.jp-TableOfContents {
  display: flex;
  flex-direction: column;
  background: var(--jp-layout-color1);
  color: var(--jp-ui-font-color1);
  font-size: var(--jp-ui-font-size1);
  height: 100%;
}

.jp-TableOfContents-placeholder {
  text-align: center;
}

.jp-TableOfContents-placeholderContent {
  color: var(--jp-content-font-color2);
  padding: 8px;
}

.jp-TableOfContents-placeholderContent > h3 {
  margin-bottom: var(--jp-content-heading-margin-bottom);
}

.jp-TableOfContents .jp-SidePanel-content {
  overflow-y: auto;
}

.jp-TableOfContents-tree {
  margin: 4px;
}

.jp-TableOfContents ol {
  list-style-type: none;
}

/* stylelint-disable-next-line selector-max-type */
.jp-TableOfContents li > ol {
  /* Align left border with triangle icon center */
  padding-left: 11px;
}

.jp-TableOfContents-content {
  /* left margin for the active heading indicator */
  margin: 0 0 0 var(--jp-private-toc-active-width);
  padding: 0;
  background-color: var(--jp-layout-color1);
}

.jp-tocItem {
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.jp-tocItem-heading {
  display: flex;
  cursor: pointer;
}

.jp-tocItem-heading:hover {
  background-color: var(--jp-layout-color2);
}

.jp-tocItem-content {
  display: block;
  padding: 4px 0;
  white-space: nowrap;
  text-overflow: ellipsis;
  overflow-x: hidden;
}

.jp-tocItem-collapser {
  height: 20px;
  margin: 2px 2px 0;
  padding: 0;
  background: none;
  border: none;
  cursor: pointer;
}

.jp-tocItem-collapser:hover {
  background-color: var(--jp-layout-color3);
}

/* Active heading indicator */

.jp-tocItem-heading::before {
  content: ' ';
  background: transparent;
  width: var(--jp-private-toc-active-width);
  height: 24px;
  position: absolute;
  left: 0;
  border-radius: var(--jp-border-radius);
}

.jp-tocItem-heading.jp-tocItem-active::before {
  background-color: var(--jp-brand-color1);
}

.jp-tocItem-heading:hover.jp-tocItem-active::before {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

.jp-Collapser {
  flex: 0 0 var(--jp-cell-collapser-width);
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
  border-radius: var(--jp-border-radius);
  opacity: 1;
}

.jp-Collapser-child {
  display: block;
  width: 100%;
  box-sizing: border-box;

  /* height: 100% doesn't work because the height of its parent is computed from content */
  position: absolute;
  top: 0;
  bottom: 0;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Hiding collapsers in print mode.

Note: input and output wrappers have "display: block" propery in print mode.
*/

@media print {
  .jp-Collapser {
    display: none;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Header/Footer
|----------------------------------------------------------------------------*/

/* Hidden by zero height by default */
.jp-CellHeader,
.jp-CellFooter {
  height: 0;
  width: 100%;
  padding: 0;
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Input
|----------------------------------------------------------------------------*/

/* All input areas */
.jp-InputArea {
  display: table;
  table-layout: fixed;
  width: 100%;
  overflow: hidden;
}

.jp-InputArea-editor {
  display: table-cell;
  overflow: hidden;
  vertical-align: top;

  /* This is the non-active, default styling */
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  background: var(--jp-cell-editor-background);
}

.jp-InputPrompt {
  display: table-cell;
  vertical-align: top;
  width: var(--jp-cell-prompt-width);
  color: var(--jp-cell-inprompt-font-color);
  font-family: var(--jp-cell-prompt-font-family);
  padding: var(--jp-code-padding);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  opacity: var(--jp-cell-prompt-opacity);
  line-height: var(--jp-code-line-height);
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;

  /* Right align prompt text, don't wrap to handle large prompt numbers */
  text-align: right;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Disable text selection */
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

/*-----------------------------------------------------------------------------
| Mobile
|----------------------------------------------------------------------------*/
@media only screen and (max-width: 760px) {
  .jp-InputArea-editor {
    display: table-row;
    margin-left: var(--jp-notebook-padding);
  }

  .jp-InputPrompt {
    display: table-row;
    text-align: left;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Placeholder {
  display: table;
  table-layout: fixed;
  width: 100%;
}

.jp-Placeholder-prompt {
  display: table-cell;
  box-sizing: border-box;
}

.jp-Placeholder-content {
  display: table-cell;
  padding: 4px 6px;
  border: 1px solid transparent;
  border-radius: 0;
  background: none;
  box-sizing: border-box;
  cursor: pointer;
}

.jp-Placeholder-contentContainer {
  display: flex;
}

.jp-Placeholder-content:hover,
.jp-InputPlaceholder > .jp-Placeholder-content:hover {
  border-color: var(--jp-layout-color3);
}

.jp-Placeholder-content .jp-MoreHorizIcon {
  width: 32px;
  height: 16px;
  border: 1px solid transparent;
  border-radius: var(--jp-border-radius);
}

.jp-Placeholder-content .jp-MoreHorizIcon:hover {
  border: 1px solid var(--jp-border-color1);
  box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.25);
  background-color: var(--jp-layout-color0);
}

.jp-PlaceholderText {
  white-space: nowrap;
  overflow-x: hidden;
  color: var(--jp-inverse-layout-color3);
  font-family: var(--jp-code-font-family);
}

.jp-InputPlaceholder > .jp-Placeholder-content {
  border-color: var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Private CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-private-cell-scrolling-output-offset: 5px;
}

/*-----------------------------------------------------------------------------
| Cell
|----------------------------------------------------------------------------*/

.jp-Cell {
  padding: var(--jp-cell-padding);
  margin: 0;
  border: none;
  outline: none;
  background: transparent;
}

/*-----------------------------------------------------------------------------
| Common input/output
|----------------------------------------------------------------------------*/

.jp-Cell-inputWrapper,
.jp-Cell-outputWrapper {
  display: flex;
  flex-direction: row;
  padding: 0;
  margin: 0;

  /* Added to reveal the box-shadow on the input and output collapsers. */
  overflow: visible;
}

/* Only input/output areas inside cells */
.jp-Cell-inputArea,
.jp-Cell-outputArea {
  flex: 1 1 auto;
}

/*-----------------------------------------------------------------------------
| Collapser
|----------------------------------------------------------------------------*/

/* Make the output collapser disappear when there is not output, but do so
 * in a manner that leaves it in the layout and preserves its width.
 */
.jp-Cell.jp-mod-noOutputs .jp-Cell-outputCollapser {
  border: none !important;
  background: transparent !important;
}

.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputCollapser {
  min-height: var(--jp-cell-collapser-min-height);
}

/*-----------------------------------------------------------------------------
| Output
|----------------------------------------------------------------------------*/

/* Put a space between input and output when there IS output */
.jp-Cell:not(.jp-mod-noOutputs) .jp-Cell-outputWrapper {
  margin-top: 5px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea {
  overflow-y: auto;
  max-height: 24em;
  margin-left: var(--jp-private-cell-scrolling-output-offset);
  resize: vertical;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea[style*='height'] {
  max-height: unset;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-Cell-outputArea::after {
  content: ' ';
  box-shadow: inset 0 0 6px 2px rgb(0 0 0 / 30%);
  width: 100%;
  height: 100%;
  position: sticky;
  bottom: 0;
  top: 0;
  margin-top: -50%;
  float: left;
  display: block;
  pointer-events: none;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-child {
  padding-top: 6px;
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-prompt {
  width: calc(
    var(--jp-cell-prompt-width) - var(--jp-private-cell-scrolling-output-offset)
  );
}

.jp-CodeCell.jp-mod-outputsScrolled .jp-OutputArea-promptOverlay {
  left: calc(-1 * var(--jp-private-cell-scrolling-output-offset));
}

/*-----------------------------------------------------------------------------
| CodeCell
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| MarkdownCell
|----------------------------------------------------------------------------*/

.jp-MarkdownOutput {
  display: table-cell;
  width: 100%;
  margin-top: 0;
  margin-bottom: 0;
  padding-left: var(--jp-code-padding);
}

.jp-MarkdownOutput.jp-RenderedHTMLCommon {
  overflow: auto;
}

/* collapseHeadingButton (show always if hiddenCellsButton is _not_ shown) */
.jp-collapseHeadingButton {
  display: flex;
  min-height: var(--jp-cell-collapser-min-height);
  font-size: var(--jp-code-font-size);
  position: absolute;
  background-color: transparent;
  background-size: 25px;
  background-repeat: no-repeat;
  background-position-x: center;
  background-position-y: top;
  background-image: var(--jp-icon-caret-down);
  right: 0;
  top: 0;
  bottom: 0;
}

.jp-collapseHeadingButton.jp-mod-collapsed {
  background-image: var(--jp-icon-caret-right);
}

/*
 set the container font size to match that of content
 so that the nested collapse buttons have the right size
*/
.jp-MarkdownCell .jp-InputPrompt {
  font-size: var(--jp-content-font-size1);
}

/*
  Align collapseHeadingButton with cell top header
  The font sizes are identical to the ones in packages/rendermime/style/base.css
*/
.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='1'] {
  font-size: var(--jp-content-font-size5);
  background-position-y: calc(0.3 * var(--jp-content-font-size5));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='2'] {
  font-size: var(--jp-content-font-size4);
  background-position-y: calc(0.3 * var(--jp-content-font-size4));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='3'] {
  font-size: var(--jp-content-font-size3);
  background-position-y: calc(0.3 * var(--jp-content-font-size3));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='4'] {
  font-size: var(--jp-content-font-size2);
  background-position-y: calc(0.3 * var(--jp-content-font-size2));
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='5'] {
  font-size: var(--jp-content-font-size1);
  background-position-y: top;
}

.jp-mod-rendered .jp-collapseHeadingButton[data-heading-level='6'] {
  font-size: var(--jp-content-font-size0);
  background-position-y: top;
}

/* collapseHeadingButton (show only on (hover,active) if hiddenCellsButton is shown) */
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-collapseHeadingButton {
  display: none;
}

.jp-Notebook.jp-mod-showHiddenCellsButton
  :is(.jp-MarkdownCell:hover, .jp-mod-active)
  .jp-collapseHeadingButton {
  display: flex;
}

/* showHiddenCellsButton (only show if jp-mod-showHiddenCellsButton is set, which
is a consequence of the showHiddenCellsButton option in Notebook Settings)*/
.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton {
  margin-left: calc(var(--jp-cell-prompt-width) + 2 * var(--jp-code-padding));
  margin-top: var(--jp-code-padding);
  border: 1px solid var(--jp-border-color2);
  background-color: var(--jp-border-color3) !important;
  color: var(--jp-content-font-color0) !important;
  display: flex;
}

.jp-Notebook.jp-mod-showHiddenCellsButton .jp-showHiddenCellsButton:hover {
  background-color: var(--jp-border-color2) !important;
}

.jp-showHiddenCellsButton {
  display: none;
}

/*-----------------------------------------------------------------------------
| Printing
|----------------------------------------------------------------------------*/

/*
Using block instead of flex to allow the use of the break-inside CSS property for
cell outputs.
*/

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

:root {
  --jp-notebook-toolbar-padding: 2px 5px 2px 2px;
}

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-NotebookPanel-toolbar {
  padding: var(--jp-notebook-toolbar-padding);

  /* disable paint containment from lumino 2.0 default strict CSS containment */
  contain: style size !important;
}

.jp-Toolbar-item.jp-Notebook-toolbarCellType .jp-select-wrapper.jp-mod-focused {
  border: none;
  box-shadow: none;
}

.jp-Notebook-toolbarCellTypeDropdown select {
  height: 24px;
  font-size: var(--jp-ui-font-size1);
  line-height: 14px;
  border-radius: 0;
  display: block;
}

.jp-Notebook-toolbarCellTypeDropdown span {
  top: 5px !important;
}

.jp-Toolbar-responsive-popup {
  position: absolute;
  height: fit-content;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: flex-end;
  border-bottom: var(--jp-border-width) solid var(--jp-toolbar-border-color);
  box-shadow: var(--jp-toolbar-box-shadow);
  background: var(--jp-toolbar-background);
  min-height: var(--jp-toolbar-micro-height);
  padding: var(--jp-notebook-toolbar-padding);
  z-index: 1;
  right: 0;
  top: 0;
}

.jp-Toolbar > .jp-Toolbar-responsive-opener {
  margin-left: auto;
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Variables
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------

/*-----------------------------------------------------------------------------
| Styles
|----------------------------------------------------------------------------*/

.jp-Notebook-ExecutionIndicator {
  position: relative;
  display: inline-block;
  height: 100%;
  z-index: 9997;
}

.jp-Notebook-ExecutionIndicator-tooltip {
  visibility: hidden;
  height: auto;
  width: max-content;
  width: -moz-max-content;
  background-color: var(--jp-layout-color2);
  color: var(--jp-ui-font-color1);
  text-align: justify;
  border-radius: 6px;
  padding: 0 5px;
  position: fixed;
  display: table;
}

.jp-Notebook-ExecutionIndicator-tooltip.up {
  transform: translateX(-50%) translateY(-100%) translateY(-32px);
}

.jp-Notebook-ExecutionIndicator-tooltip.down {
  transform: translateX(calc(-100% + 16px)) translateY(5px);
}

.jp-Notebook-ExecutionIndicator-tooltip.hidden {
  display: none;
}

.jp-Notebook-ExecutionIndicator:hover .jp-Notebook-ExecutionIndicator-tooltip {
  visibility: visible;
}

.jp-Notebook-ExecutionIndicator span {
  font-size: var(--jp-ui-font-size1);
  font-family: var(--jp-ui-font-family);
  color: var(--jp-ui-font-color1);
  line-height: 24px;
  display: block;
}

.jp-Notebook-ExecutionIndicator-progress-bar {
  display: flex;
  justify-content: center;
  height: 100%;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

/*
 * Execution indicator
 */
.jp-tocItem-content::after {
  content: '';

  /* Must be identical to form a circle */
  width: 12px;
  height: 12px;
  background: none;
  border: none;
  position: absolute;
  right: 0;
}

.jp-tocItem-content[data-running='0']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background: none;
}

.jp-tocItem-content[data-running='1']::after {
  border-radius: 50%;
  border: var(--jp-border-width) solid var(--jp-inverse-layout-color3);
  background-color: var(--jp-inverse-layout-color3);
}

.jp-tocItem-content[data-running='0'],
.jp-tocItem-content[data-running='1'] {
  margin-right: 12px;
}

/*
 * Copyright (c) Jupyter Development Team.
 * Distributed under the terms of the Modified BSD License.
 */

.jp-Notebook-footer {
  height: 27px;
  margin-left: calc(
    var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
      var(--jp-cell-padding)
  );
  width: calc(
    100% -
      (
        var(--jp-cell-prompt-width) + var(--jp-cell-collapser-width) +
          var(--jp-cell-padding) + var(--jp-cell-padding)
      )
  );
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  color: var(--jp-ui-font-color3);
  margin-top: 6px;
  background: none;
  cursor: pointer;
}

.jp-Notebook-footer:focus {
  border-color: var(--jp-cell-editor-active-border-color);
}

/* For devices that support hovering, hide footer until hover */
@media (hover: hover) {
  .jp-Notebook-footer {
    opacity: 0;
  }

  .jp-Notebook-footer:focus,
  .jp-Notebook-footer:hover {
    opacity: 1;
  }
}

/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| Imports
|----------------------------------------------------------------------------*/

/*-----------------------------------------------------------------------------
| CSS variables
|----------------------------------------------------------------------------*/

:root {
  --jp-side-by-side-output-size: 1fr;
  --jp-side-by-side-resized-cell: var(--jp-side-by-side-output-size);
  --jp-private-notebook-dragImage-width: 304px;
  --jp-private-notebook-dragImage-height: 36px;
  --jp-private-notebook-selected-color: var(--md-blue-400);
  --jp-private-notebook-active-color: var(--md-green-400);
}

/*-----------------------------------------------------------------------------
| Notebook
|----------------------------------------------------------------------------*/

/* stylelint-disable selector-max-class */

.jp-NotebookPanel {
  display: block;
  height: 100%;
}

.jp-NotebookPanel.jp-Document {
  min-width: 240px;
  min-height: 120px;
}

.jp-Notebook {
  padding: var(--jp-notebook-padding);
  outline: none;
  overflow: auto;
  background: var(--jp-layout-color0);
}

.jp-Notebook.jp-mod-scrollPastEnd::after {
  display: block;
  content: '';
  min-height: var(--jp-notebook-scroll-padding);
}

.jp-MainAreaWidget-ContainStrict .jp-Notebook * {
  contain: strict;
}

.jp-Notebook .jp-Cell {
  overflow: visible;
}

.jp-Notebook .jp-Cell .jp-InputPrompt {
  cursor: move;
}

/*-----------------------------------------------------------------------------
| Notebook state related styling
|
| The notebook and cells each have states, here are the possibilities:
|
| - Notebook
|   - Command
|   - Edit
| - Cell
|   - None
|   - Active (only one can be active)
|   - Selected (the cells actions are applied to)
|   - Multiselected (when multiple selected, the cursor)
|   - No outputs
|----------------------------------------------------------------------------*/

/* Command or edit modes */

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-InputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

.jp-Notebook .jp-Cell:not(.jp-mod-active) .jp-OutputPrompt {
  opacity: var(--jp-cell-prompt-not-active-opacity);
  color: var(--jp-cell-prompt-not-active-font-color);
}

/* cell is active */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser {
  background: var(--jp-brand-color1);
}

/* cell is dirty */
.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt {
  color: var(--jp-warn-color1);
}

.jp-Notebook .jp-Cell.jp-mod-dirty .jp-InputPrompt::before {
  color: var(--jp-warn-color1);
  content: '•';
}

.jp-Notebook .jp-Cell.jp-mod-active.jp-mod-dirty .jp-Collapser {
  background: var(--jp-warn-color1);
}

/* collapser is hovered */
.jp-Notebook .jp-Cell .jp-Collapser:hover {
  box-shadow: var(--jp-elevation-z2);
  background: var(--jp-brand-color1);
  opacity: var(--jp-cell-collapser-not-active-hover-opacity);
}

/* cell is active and collapser is hovered */
.jp-Notebook .jp-Cell.jp-mod-active .jp-Collapser:hover {
  background: var(--jp-brand-color0);
  opacity: 1;
}

/* Command mode */

.jp-Notebook.jp-mod-commandMode .jp-Cell.jp-mod-selected {
  background: var(--jp-notebook-multiselected-color);
}

.jp-Notebook.jp-mod-commandMode
  .jp-Cell.jp-mod-active.jp-mod-selected:not(.jp-mod-multiSelected) {
  background: transparent;
}

/* Edit mode */

.jp-Notebook.jp-mod-editMode .jp-Cell.jp-mod-active .jp-InputArea-editor {
  border: var(--jp-border-width) solid var(--jp-cell-editor-active-border-color);
  box-shadow: var(--jp-input-box-shadow);
  background-color: var(--jp-cell-editor-active-background);
}

/*-----------------------------------------------------------------------------
| Notebook drag and drop
|----------------------------------------------------------------------------*/

.jp-Notebook-cell.jp-mod-dropSource {
  opacity: 0.5;
}

.jp-Notebook-cell.jp-mod-dropTarget,
.jp-Notebook.jp-mod-commandMode
  .jp-Notebook-cell.jp-mod-active.jp-mod-selected.jp-mod-dropTarget {
  border-top-color: var(--jp-private-notebook-selected-color);
  border-top-style: solid;
  border-top-width: 2px;
}

.jp-dragImage {
  display: block;
  flex-direction: row;
  width: var(--jp-private-notebook-dragImage-width);
  height: var(--jp-private-notebook-dragImage-height);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background);
  overflow: visible;
}

.jp-dragImage-singlePrompt {
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

.jp-dragImage .jp-dragImage-content {
  flex: 1 1 auto;
  z-index: 2;
  font-size: var(--jp-code-font-size);
  font-family: var(--jp-code-font-family);
  line-height: var(--jp-code-line-height);
  padding: var(--jp-code-padding);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  background: var(--jp-cell-editor-background-color);
  color: var(--jp-content-font-color3);
  text-align: left;
  margin: 4px 4px 4px 0;
}

.jp-dragImage .jp-dragImage-prompt {
  flex: 0 0 auto;
  min-width: 36px;
  color: var(--jp-cell-inprompt-font-color);
  padding: var(--jp-code-padding);
  padding-left: 12px;
  font-family: var(--jp-cell-prompt-font-family);
  letter-spacing: var(--jp-cell-prompt-letter-spacing);
  line-height: 1.9;
  font-size: var(--jp-code-font-size);
  border: var(--jp-border-width) solid transparent;
}

.jp-dragImage-multipleBack {
  z-index: -1;
  position: absolute;
  height: 32px;
  width: 300px;
  top: 8px;
  left: 8px;
  background: var(--jp-layout-color2);
  border: var(--jp-border-width) solid var(--jp-input-border-color);
  box-shadow: 2px 2px 4px 0 rgba(0, 0, 0, 0.12);
}

/*-----------------------------------------------------------------------------
| Cell toolbar
|----------------------------------------------------------------------------*/

.jp-NotebookTools {
  display: block;
  min-width: var(--jp-sidebar-min-width);
  color: var(--jp-ui-font-color1);
  background: var(--jp-layout-color1);

  /* This is needed so that all font sizing of children done in ems is
    * relative to this base size */
  font-size: var(--jp-ui-font-size1);
  overflow: auto;
}

.jp-ActiveCellTool {
  padding: 12px 0;
  display: flex;
}

.jp-ActiveCellTool-Content {
  flex: 1 1 auto;
}

.jp-ActiveCellTool .jp-ActiveCellTool-CellContent {
  background: var(--jp-cell-editor-background);
  border: var(--jp-border-width) solid var(--jp-cell-editor-border-color);
  border-radius: 0;
  min-height: 29px;
}

.jp-ActiveCellTool .jp-InputPrompt {
  min-width: calc(var(--jp-cell-prompt-width) * 0.75);
}

.jp-ActiveCellTool-CellContent > pre {
  padding: 5px 4px;
  margin: 0;
  white-space: normal;
}

.jp-MetadataEditorTool {
  flex-direction: column;
  padding: 12px 0;
}

.jp-RankedPanel > :not(:first-child) {
  margin-top: 12px;
}

.jp-KeySelector select.jp-mod-styled {
  font-size: var(--jp-ui-font-size1);
  color: var(--jp-ui-font-color0);
  border: var(--jp-border-width) solid var(--jp-border-color1);
}

.jp-KeySelector label,
.jp-MetadataEditorTool label,
.jp-NumberSetter label {
  line-height: 1.4;
}

.jp-NotebookTools .jp-select-wrapper {
  margin-top: 4px;
  margin-bottom: 0;
}

.jp-NumberSetter input {
  width: 100%;
  margin-top: 4px;
}

.jp-NotebookTools .jp-Collapse {
  margin-top: 16px;
}

/*-----------------------------------------------------------------------------
| Presentation Mode (.jp-mod-presentationMode)
|----------------------------------------------------------------------------*/

.jp-mod-presentationMode .jp-Notebook {
  --jp-content-font-size1: var(--jp-content-presentation-font-size1);
  --jp-code-font-size: var(--jp-code-presentation-font-size);
}

.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-InputPrompt,
.jp-mod-presentationMode .jp-Notebook .jp-Cell .jp-OutputPrompt {
  flex: 0 0 110px;
}

/*-----------------------------------------------------------------------------
| Side-by-side Mode (.jp-mod-sideBySide)
|----------------------------------------------------------------------------*/
.jp-mod-sideBySide.jp-Notebook .jp-Notebook-cell {
  margin-top: 3em;
  margin-bottom: 3em;
  margin-left: 5%;
  margin-right: 5%;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell {
  display: grid;
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-output-size)
    );
  grid-template-rows: auto minmax(0, 1fr) auto;
  grid-template-areas:
    'header header header'
    'input handle output'
    'footer footer footer';
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell.jp-mod-resizedCell {
  grid-template-columns: minmax(0, 1fr) min-content minmax(
      0,
      var(--jp-side-by-side-resized-cell)
    );
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellHeader {
  grid-area: header;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-inputWrapper {
  grid-area: input;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-Cell-outputWrapper {
  /* overwrite the default margin (no vertical separation needed in side by side move */
  margin-top: 0;
  grid-area: output;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellFooter {
  grid-area: footer;
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle {
  grid-area: handle;
  user-select: none;
  display: block;
  height: 100%;
  cursor: ew-resize;
  padding: 0 var(--jp-cell-padding);
}

.jp-mod-sideBySide.jp-Notebook .jp-CodeCell .jp-CellResizeHandle::after {
  content: '';
  display: block;
  background: var(--jp-border-color2);
  height: 100%;
  width: 5px;
}

.jp-mod-sideBySide.jp-Notebook
  .jp-CodeCell.jp-mod-resizedCell
  .jp-CellResizeHandle::after {
  background: var(--jp-border-color0);
}

.jp-CellResizeHandle {
  display: none;
}

/*-----------------------------------------------------------------------------
| Placeholder
|----------------------------------------------------------------------------*/

.jp-Cell-Placeholder {
  padding-left: 55px;
}

.jp-Cell-Placeholder-wrapper {
  background: #fff;
  border: 1px solid;
  border-color: #e5e6e9 #dfe0e4 #d0d1d5;
  border-radius: 4px;
  -webkit-border-radius: 4px;
  margin: 10px 15px;
}

.jp-Cell-Placeholder-wrapper-inner {
  padding: 15px;
  position: relative;
}

.jp-Cell-Placeholder-wrapper-body {
  background-repeat: repeat;
  background-size: 50% auto;
}

.jp-Cell-Placeholder-wrapper-body div {
  background: #f6f7f8;
  background-image: -webkit-linear-gradient(
    left,
    #f6f7f8 0%,
    #edeef1 20%,
    #f6f7f8 40%,
    #f6f7f8 100%
  );
  background-repeat: no-repeat;
  background-size: 800px 104px;
  height: 104px;
  position: absolute;
  right: 15px;
  left: 15px;
  top: 15px;
}

div.jp-Cell-Placeholder-h1 {
  top: 20px;
  height: 20px;
  left: 15px;
  width: 150px;
}

div.jp-Cell-Placeholder-h2 {
  left: 15px;
  top: 50px;
  height: 10px;
  width: 100px;
}

div.jp-Cell-Placeholder-content-1,
div.jp-Cell-Placeholder-content-2,
div.jp-Cell-Placeholder-content-3 {
  left: 15px;
  right: 15px;
  height: 10px;
}

div.jp-Cell-Placeholder-content-1 {
  top: 100px;
}

div.jp-Cell-Placeholder-content-2 {
  top: 120px;
}

div.jp-Cell-Placeholder-content-3 {
  top: 140px;
}

</style>
<style type="text/css">
/*-----------------------------------------------------------------------------
| Copyright (c) Jupyter Development Team.
| Distributed under the terms of the Modified BSD License.
|----------------------------------------------------------------------------*/

/*
The following CSS variables define the main, public API for styling JupyterLab.
These variables should be used by all plugins wherever possible. In other
words, plugins should not define custom colors, sizes, etc unless absolutely
necessary. This enables users to change the visual theme of JupyterLab
by changing these variables.

Many variables appear in an ordered sequence (0,1,2,3). These sequences
are designed to work well together, so for example, `--jp-border-color1` should
be used with `--jp-layout-color1`. The numbers have the following meanings:

* 0: super-primary, reserved for special emphasis
* 1: primary, most important under normal situations
* 2: secondary, next most important under normal situations
* 3: tertiary, next most important under normal situations

Throughout JupyterLab, we are mostly following principles from Google's
Material Design when selecting colors. We are not, however, following
all of MD as it is not optimized for dense, information rich UIs.
*/

:root {
  /* Elevation
   *
   * We style box-shadows using Material Design's idea of elevation. These particular numbers are taken from here:
   *
   * https://github.com/material-components/material-components-web
   * https://material-components-web.appspot.com/elevation.html
   */

  --jp-shadow-base-lightness: 0;
  --jp-shadow-umbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.2
  );
  --jp-shadow-penumbra-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.14
  );
  --jp-shadow-ambient-color: rgba(
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    var(--jp-shadow-base-lightness),
    0.12
  );
  --jp-elevation-z0: none;
  --jp-elevation-z1: 0 2px 1px -1px var(--jp-shadow-umbra-color),
    0 1px 1px 0 var(--jp-shadow-penumbra-color),
    0 1px 3px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z2: 0 3px 1px -2px var(--jp-shadow-umbra-color),
    0 2px 2px 0 var(--jp-shadow-penumbra-color),
    0 1px 5px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z4: 0 2px 4px -1px var(--jp-shadow-umbra-color),
    0 4px 5px 0 var(--jp-shadow-penumbra-color),
    0 1px 10px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z6: 0 3px 5px -1px var(--jp-shadow-umbra-color),
    0 6px 10px 0 var(--jp-shadow-penumbra-color),
    0 1px 18px 0 var(--jp-shadow-ambient-color);
  --jp-elevation-z8: 0 5px 5px -3px var(--jp-shadow-umbra-color),
    0 8px 10px 1px var(--jp-shadow-penumbra-color),
    0 3px 14px 2px var(--jp-shadow-ambient-color);
  --jp-elevation-z12: 0 7px 8px -4px var(--jp-shadow-umbra-color),
    0 12px 17px 2px var(--jp-shadow-penumbra-color),
    0 5px 22px 4px var(--jp-shadow-ambient-color);
  --jp-elevation-z16: 0 8px 10px -5px var(--jp-shadow-umbra-color),
    0 16px 24px 2px var(--jp-shadow-penumbra-color),
    0 6px 30px 5px var(--jp-shadow-ambient-color);
  --jp-elevation-z20: 0 10px 13px -6px var(--jp-shadow-umbra-color),
    0 20px 31px 3px var(--jp-shadow-penumbra-color),
    0 8px 38px 7px var(--jp-shadow-ambient-color);
  --jp-elevation-z24: 0 11px 15px -7px var(--jp-shadow-umbra-color),
    0 24px 38px 3px var(--jp-shadow-penumbra-color),
    0 9px 46px 8px var(--jp-shadow-ambient-color);

  /* Borders
   *
   * The following variables, specify the visual styling of borders in JupyterLab.
   */

  --jp-border-width: 1px;
  --jp-border-color0: var(--md-grey-400);
  --jp-border-color1: var(--md-grey-400);
  --jp-border-color2: var(--md-grey-300);
  --jp-border-color3: var(--md-grey-200);
  --jp-inverse-border-color: var(--md-grey-600);
  --jp-border-radius: 2px;

  /* UI Fonts
   *
   * The UI font CSS variables are used for the typography all of the JupyterLab
   * user interface elements that are not directly user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-ui-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-ui-font-scale-factor: 1.2;
  --jp-ui-font-size0: 0.83333em;
  --jp-ui-font-size1: 13px; /* Base font size */
  --jp-ui-font-size2: 1.2em;
  --jp-ui-font-size3: 1.44em;
  --jp-ui-font-family: system-ui, -apple-system, blinkmacsystemfont, 'Segoe UI',
    helvetica, arial, sans-serif, 'Apple Color Emoji', 'Segoe UI Emoji',
    'Segoe UI Symbol';

  /*
   * Use these font colors against the corresponding main layout colors.
   * In a light theme, these go from dark to light.
   */

  /* Defaults use Material Design specification */
  --jp-ui-font-color0: rgba(0, 0, 0, 1);
  --jp-ui-font-color1: rgba(0, 0, 0, 0.87);
  --jp-ui-font-color2: rgba(0, 0, 0, 0.54);
  --jp-ui-font-color3: rgba(0, 0, 0, 0.38);

  /*
   * Use these against the brand/accent/warn/error colors.
   * These will typically go from light to darker, in both a dark and light theme.
   */

  --jp-ui-inverse-font-color0: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color1: rgba(255, 255, 255, 1);
  --jp-ui-inverse-font-color2: rgba(255, 255, 255, 0.7);
  --jp-ui-inverse-font-color3: rgba(255, 255, 255, 0.5);

  /* Content Fonts
   *
   * Content font variables are used for typography of user generated content.
   *
   * The font sizing here is done assuming that the body font size of --jp-content-font-size1
   * is applied to a parent element. When children elements, such as headings, are sized
   * in em all things will be computed relative to that body size.
   */

  --jp-content-line-height: 1.6;
  --jp-content-font-scale-factor: 1.2;
  --jp-content-font-size0: 0.83333em;
  --jp-content-font-size1: 14px; /* Base font size */
  --jp-content-font-size2: 1.2em;
  --jp-content-font-size3: 1.44em;
  --jp-content-font-size4: 1.728em;
  --jp-content-font-size5: 2.0736em;

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-content-presentation-font-size1: 17px;
  --jp-content-heading-line-height: 1;
  --jp-content-heading-margin-top: 1.2em;
  --jp-content-heading-margin-bottom: 0.8em;
  --jp-content-heading-font-weight: 500;

  /* Defaults use Material Design specification */
  --jp-content-font-color0: rgba(0, 0, 0, 1);
  --jp-content-font-color1: rgba(0, 0, 0, 0.87);
  --jp-content-font-color2: rgba(0, 0, 0, 0.54);
  --jp-content-font-color3: rgba(0, 0, 0, 0.38);
  --jp-content-link-color: var(--md-blue-900);
  --jp-content-font-family: system-ui, -apple-system, blinkmacsystemfont,
    'Segoe UI', helvetica, arial, sans-serif, 'Apple Color Emoji',
    'Segoe UI Emoji', 'Segoe UI Symbol';

  /*
   * Code Fonts
   *
   * Code font variables are used for typography of code and other monospaces content.
   */

  --jp-code-font-size: 13px;
  --jp-code-line-height: 1.3077; /* 17px for 13px base */
  --jp-code-padding: 5px; /* 5px for 13px base, codemirror highlighting needs integer px value */
  --jp-code-font-family-default: menlo, consolas, 'DejaVu Sans Mono', monospace;
  --jp-code-font-family: var(--jp-code-font-family-default);

  /* This gives a magnification of about 125% in presentation mode over normal. */
  --jp-code-presentation-font-size: 16px;

  /* may need to tweak cursor width if you change font size */
  --jp-code-cursor-width0: 1.4px;
  --jp-code-cursor-width1: 2px;
  --jp-code-cursor-width2: 4px;

  /* Layout
   *
   * The following are the main layout colors use in JupyterLab. In a light
   * theme these would go from light to dark.
   */

  --jp-layout-color0: white;
  --jp-layout-color1: white;
  --jp-layout-color2: var(--md-grey-200);
  --jp-layout-color3: var(--md-grey-400);
  --jp-layout-color4: var(--md-grey-600);

  /* Inverse Layout
   *
   * The following are the inverse layout colors use in JupyterLab. In a light
   * theme these would go from dark to light.
   */

  --jp-inverse-layout-color0: #111;
  --jp-inverse-layout-color1: var(--md-grey-900);
  --jp-inverse-layout-color2: var(--md-grey-800);
  --jp-inverse-layout-color3: var(--md-grey-700);
  --jp-inverse-layout-color4: var(--md-grey-600);

  /* Brand/accent */

  --jp-brand-color0: var(--md-blue-900);
  --jp-brand-color1: var(--md-blue-700);
  --jp-brand-color2: var(--md-blue-300);
  --jp-brand-color3: var(--md-blue-100);
  --jp-brand-color4: var(--md-blue-50);
  --jp-accent-color0: var(--md-green-900);
  --jp-accent-color1: var(--md-green-700);
  --jp-accent-color2: var(--md-green-300);
  --jp-accent-color3: var(--md-green-100);

  /* State colors (warn, error, success, info) */

  --jp-warn-color0: var(--md-orange-900);
  --jp-warn-color1: var(--md-orange-700);
  --jp-warn-color2: var(--md-orange-300);
  --jp-warn-color3: var(--md-orange-100);
  --jp-error-color0: var(--md-red-900);
  --jp-error-color1: var(--md-red-700);
  --jp-error-color2: var(--md-red-300);
  --jp-error-color3: var(--md-red-100);
  --jp-success-color0: var(--md-green-900);
  --jp-success-color1: var(--md-green-700);
  --jp-success-color2: var(--md-green-300);
  --jp-success-color3: var(--md-green-100);
  --jp-info-color0: var(--md-cyan-900);
  --jp-info-color1: var(--md-cyan-700);
  --jp-info-color2: var(--md-cyan-300);
  --jp-info-color3: var(--md-cyan-100);

  /* Cell specific styles */

  --jp-cell-padding: 5px;
  --jp-cell-collapser-width: 8px;
  --jp-cell-collapser-min-height: 20px;
  --jp-cell-collapser-not-active-hover-opacity: 0.6;
  --jp-cell-editor-background: var(--md-grey-100);
  --jp-cell-editor-border-color: var(--md-grey-300);
  --jp-cell-editor-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-cell-editor-active-background: var(--jp-layout-color0);
  --jp-cell-editor-active-border-color: var(--jp-brand-color1);
  --jp-cell-prompt-width: 64px;
  --jp-cell-prompt-font-family: var(--jp-code-font-family-default);
  --jp-cell-prompt-letter-spacing: 0;
  --jp-cell-prompt-opacity: 1;
  --jp-cell-prompt-not-active-opacity: 0.5;
  --jp-cell-prompt-not-active-font-color: var(--md-grey-700);

  /* A custom blend of MD grey and blue 600
   * See https://meyerweb.com/eric/tools/color-blend/#546E7A:1E88E5:5:hex */
  --jp-cell-inprompt-font-color: #307fc1;

  /* A custom blend of MD grey and orange 600
   * https://meyerweb.com/eric/tools/color-blend/#546E7A:F4511E:5:hex */
  --jp-cell-outprompt-font-color: #bf5b3d;

  /* Notebook specific styles */

  --jp-notebook-padding: 10px;
  --jp-notebook-select-background: var(--jp-layout-color1);
  --jp-notebook-multiselected-color: var(--md-blue-50);

  /* The scroll padding is calculated to fill enough space at the bottom of the
  notebook to show one single-line cell (with appropriate padding) at the top
  when the notebook is scrolled all the way to the bottom. We also subtract one
  pixel so that no scrollbar appears if we have just one single-line cell in the
  notebook. This padding is to enable a 'scroll past end' feature in a notebook.
  */
  --jp-notebook-scroll-padding: calc(
    100% - var(--jp-code-font-size) * var(--jp-code-line-height) -
      var(--jp-code-padding) - var(--jp-cell-padding) - 1px
  );

  /* Rendermime styles */

  --jp-rendermime-error-background: #fdd;
  --jp-rendermime-table-row-background: var(--md-grey-100);
  --jp-rendermime-table-row-hover-background: var(--md-light-blue-50);

  /* Dialog specific styles */

  --jp-dialog-background: rgba(0, 0, 0, 0.25);

  /* Console specific styles */

  --jp-console-padding: 10px;

  /* Toolbar specific styles */

  --jp-toolbar-border-color: var(--jp-border-color1);
  --jp-toolbar-micro-height: 8px;
  --jp-toolbar-background: var(--jp-layout-color1);
  --jp-toolbar-box-shadow: 0 0 2px 0 rgba(0, 0, 0, 0.24);
  --jp-toolbar-header-margin: 4px 4px 0 4px;
  --jp-toolbar-active-background: var(--md-grey-300);

  /* Statusbar specific styles */

  --jp-statusbar-height: 24px;

  /* Input field styles */

  --jp-input-box-shadow: inset 0 0 2px var(--md-blue-300);
  --jp-input-active-background: var(--jp-layout-color1);
  --jp-input-hover-background: var(--jp-layout-color1);
  --jp-input-background: var(--md-grey-100);
  --jp-input-border-color: var(--jp-inverse-border-color);
  --jp-input-active-border-color: var(--jp-brand-color1);
  --jp-input-active-box-shadow-color: rgba(19, 124, 189, 0.3);

  /* General editor styles */

  --jp-editor-selected-background: #d9d9d9;
  --jp-editor-selected-focused-background: #d7d4f0;
  --jp-editor-cursor-color: var(--jp-ui-font-color0);

  /* Code mirror specific styles */

  --jp-mirror-editor-keyword-color: #008000;
  --jp-mirror-editor-atom-color: #88f;
  --jp-mirror-editor-number-color: #080;
  --jp-mirror-editor-def-color: #00f;
  --jp-mirror-editor-variable-color: var(--md-grey-900);
  --jp-mirror-editor-variable-2-color: rgb(0, 54, 109);
  --jp-mirror-editor-variable-3-color: #085;
  --jp-mirror-editor-punctuation-color: #05a;
  --jp-mirror-editor-property-color: #05a;
  --jp-mirror-editor-operator-color: #a2f;
  --jp-mirror-editor-comment-color: #408080;
  --jp-mirror-editor-string-color: #ba2121;
  --jp-mirror-editor-string-2-color: #708;
  --jp-mirror-editor-meta-color: #a2f;
  --jp-mirror-editor-qualifier-color: #555;
  --jp-mirror-editor-builtin-color: #008000;
  --jp-mirror-editor-bracket-color: #997;
  --jp-mirror-editor-tag-color: #170;
  --jp-mirror-editor-attribute-color: #00c;
  --jp-mirror-editor-header-color: blue;
  --jp-mirror-editor-quote-color: #090;
  --jp-mirror-editor-link-color: #00c;
  --jp-mirror-editor-error-color: #f00;
  --jp-mirror-editor-hr-color: #999;

  /*
    RTC user specific colors.
    These colors are used for the cursor, username in the editor,
    and the icon of the user.
  */

  --jp-collaborator-color1: #ffad8e;
  --jp-collaborator-color2: #dac83d;
  --jp-collaborator-color3: #72dd76;
  --jp-collaborator-color4: #00e4d0;
  --jp-collaborator-color5: #45d4ff;
  --jp-collaborator-color6: #e2b1ff;
  --jp-collaborator-color7: #ff9de6;

  /* Vega extension styles */

  --jp-vega-background: white;

  /* Sidebar-related styles */

  --jp-sidebar-min-width: 250px;

  /* Search-related styles */

  --jp-search-toggle-off-opacity: 0.5;
  --jp-search-toggle-hover-opacity: 0.8;
  --jp-search-toggle-on-opacity: 1;
  --jp-search-selected-match-background-color: rgb(245, 200, 0);
  --jp-search-selected-match-color: black;
  --jp-search-unselected-match-background-color: var(
    --jp-inverse-layout-color0
  );
  --jp-search-unselected-match-color: var(--jp-ui-inverse-font-color0);

  /* Icon colors that work well with light or dark backgrounds */
  --jp-icon-contrast-color0: var(--md-purple-600);
  --jp-icon-contrast-color1: var(--md-green-600);
  --jp-icon-contrast-color2: var(--md-pink-600);
  --jp-icon-contrast-color3: var(--md-blue-600);

  /* Button colors */
  --jp-accept-color-normal: var(--md-blue-700);
  --jp-accept-color-hover: var(--md-blue-800);
  --jp-accept-color-active: var(--md-blue-900);
  --jp-warn-color-normal: var(--md-red-700);
  --jp-warn-color-hover: var(--md-red-800);
  --jp-warn-color-active: var(--md-red-900);
  --jp-reject-color-normal: var(--md-grey-600);
  --jp-reject-color-hover: var(--md-grey-700);
  --jp-reject-color-active: var(--md-grey-800);

  /* File or activity icons and switch semantic variables */
  --jp-jupyter-icon-color: #f37626;
  --jp-notebook-icon-color: #f37626;
  --jp-json-icon-color: var(--md-orange-700);
  --jp-console-icon-background-color: var(--md-blue-700);
  --jp-console-icon-color: white;
  --jp-terminal-icon-background-color: var(--md-grey-800);
  --jp-terminal-icon-color: var(--md-grey-200);
  --jp-text-editor-icon-color: var(--md-grey-700);
  --jp-inspector-icon-color: var(--md-grey-700);
  --jp-switch-color: var(--md-grey-400);
  --jp-switch-true-position-color: var(--md-orange-900);
}
</style>
<style type="text/css">
/* Force rendering true colors when outputing to pdf */
* {
  -webkit-print-color-adjust: exact;
}

/* Misc */
a.anchor-link {
  display: none;
}

/* Input area styling */
.jp-InputArea {
  overflow: hidden;
}

.jp-InputArea-editor {
  overflow: hidden;
}

.cm-editor.cm-s-jupyter .highlight pre {
/* weird, but --jp-code-padding defined to be 5px but 4px horizontal padding is hardcoded for pre.cm-line */
  padding: var(--jp-code-padding) 4px;
  margin: 0;

  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
  color: inherit;

}

.jp-OutputArea-output pre {
  line-height: inherit;
  font-family: inherit;
}

.jp-RenderedText pre {
  color: var(--jp-content-font-color1);
  font-size: var(--jp-code-font-size);
}

/* Hiding the collapser by default */
.jp-Collapser {
  display: none;
}

@page {
    margin: 0.5in; /* Margin for each printed piece of paper */
}

@media print {
  .jp-Cell-inputWrapper,
  .jp-Cell-outputWrapper {
    display: block;
  }
}
</style>
<!-- Load mathjax -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/latest.js?config=TeX-AMS_CHTML-full,Safe"> </script>
<!-- MathJax configuration -->
<script type="text/x-mathjax-config">
    init_mathjax = function() {
        if (window.MathJax) {
        // MathJax loaded
            MathJax.Hub.Config({
                TeX: {
                    equationNumbers: {
                    autoNumber: "AMS",
                    useLabelIds: true
                    }
                },
                tex2jax: {
                    inlineMath: [ ['$','$'], ["\\(","\\)"] ],
                    displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
                    processEscapes: true,
                    processEnvironments: true
                },
                displayAlign: 'center',
                CommonHTML: {
                    linebreaks: {
                    automatic: true
                    }
                }
            });

            MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
        }
    }
    init_mathjax();
    </script>
<!-- End of mathjax configuration --><script type="module">
  document.addEventListener("DOMContentLoaded", async () => {
    const diagrams = document.querySelectorAll(".jp-Mermaid > pre.mermaid");
    // do not load mermaidjs if not needed
    if (!diagrams.length) {
      return;
    }
    const mermaid = (await import("https://cdnjs.cloudflare.com/ajax/libs/mermaid/10.7.0/mermaid.esm.min.mjs")).default;
    const parser = new DOMParser();

    mermaid.initialize({
      maxTextSize: 100000,
      maxEdges: 100000,
      startOnLoad: false,
      fontFamily: window
        .getComputedStyle(document.body)
        .getPropertyValue("--jp-ui-font-family"),
      theme: document.querySelector("body[data-jp-theme-light='true']")
        ? "default"
        : "dark",
    });

    let _nextMermaidId = 0;

    function makeMermaidImage(svg) {
      const img = document.createElement("img");
      const doc = parser.parseFromString(svg, "image/svg+xml");
      const svgEl = doc.querySelector("svg");
      const { maxWidth } = svgEl?.style || {};
      const firstTitle = doc.querySelector("title");
      const firstDesc = doc.querySelector("desc");

      img.setAttribute("src", `data:image/svg+xml,${encodeURIComponent(svg)}`);
      if (maxWidth) {
        img.width = parseInt(maxWidth);
      }
      if (firstTitle) {
        img.setAttribute("alt", firstTitle.textContent);
      }
      if (firstDesc) {
        const caption = document.createElement("figcaption");
        caption.className = "sr-only";
        caption.textContent = firstDesc.textContent;
        return [img, caption];
      }
      return [img];
    }

    async function makeMermaidError(text) {
      let errorMessage = "";
      try {
        await mermaid.parse(text);
      } catch (err) {
        errorMessage = `${err}`;
      }

      const result = document.createElement("details");
      result.className = 'jp-RenderedMermaid-Details';
      const summary = document.createElement("summary");
      summary.className = 'jp-RenderedMermaid-Summary';
      const pre = document.createElement("pre");
      const code = document.createElement("code");
      code.innerText = text;
      pre.appendChild(code);
      summary.appendChild(pre);
      result.appendChild(summary);

      const warning = document.createElement("pre");
      warning.innerText = errorMessage;
      result.appendChild(warning);
      return [result];
    }

    async function renderOneMarmaid(src) {
      const id = `jp-mermaid-${_nextMermaidId++}`;
      const parent = src.parentNode;
      let raw = src.textContent.trim();
      const el = document.createElement("div");
      el.style.visibility = "hidden";
      document.body.appendChild(el);
      let results = null;
      let output = null;
      try {
        const { svg } = await mermaid.render(id, raw, el);
        results = makeMermaidImage(svg);
        output = document.createElement("figure");
        results.map(output.appendChild, output);
      } catch (err) {
        parent.classList.add("jp-mod-warning");
        results = await makeMermaidError(raw);
        output = results[0];
      } finally {
        el.remove();
      }
      parent.classList.add("jp-RenderedMermaid");
      parent.appendChild(output);
    }

    void Promise.all([...diagrams].map(renderOneMarmaid));
  });
</script>
<style>
  .jp-Mermaid:not(.jp-RenderedMermaid) {
    display: none;
  }

  .jp-RenderedMermaid {
    overflow: auto;
    display: flex;
  }

  .jp-RenderedMermaid.jp-mod-warning {
    width: auto;
    padding: 0.5em;
    margin-top: 0.5em;
    border: var(--jp-border-width) solid var(--jp-warn-color2);
    border-radius: var(--jp-border-radius);
    color: var(--jp-ui-font-color1);
    font-size: var(--jp-ui-font-size1);
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .jp-RenderedMermaid figure {
    margin: 0;
    overflow: auto;
    max-width: 100%;
  }

  .jp-RenderedMermaid img {
    max-width: 100%;
  }

  .jp-RenderedMermaid-Details > pre {
    margin-top: 1em;
  }

  .jp-RenderedMermaid-Summary {
    color: var(--jp-warn-color2);
  }

  .jp-RenderedMermaid:not(.jp-mod-warning) pre {
    display: none;
  }

  .jp-RenderedMermaid-Summary > pre {
    display: inline-block;
    white-space: normal;
  }
</style>
<!-- End of mermaid configuration --></head>
<body class="jp-Notebook" data-jp-theme-light="true" data-jp-theme-name="JupyterLab Light">
<main><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">

<!-- Beginning of newly added comment saying I'm loading in some libraries -->
<h2> Load In Needed Libraries </h2>
<!-- End of newly added comment saying I'm loading in some libraries -->
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [7]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">tensorflow</span> <span class="k">as</span> <span class="nn">tf</span>

<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">accuracy_score</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">StandardScaler</span>
<span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="kn">import</span> <span class="n">MinMaxScaler</span>

<span class="kn">import</span> <span class="nn">os</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of the deleted os.getcwd cell input and output -->
<!-- Ending of the deleted os.getcwd cell input and output  -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of the deleted pip install nbconvert cell, input only  -->

<!-- End of the deleted pip install nbconvert cell  input only -->

<!-- Beginning of the deleted pip install nbconvert cell  output only -->


<!-- End of the deleted pip install nbconvert cell  output only -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">

<!-- Beginning of the deleted google.colab cell input and output -->


<!-- End of the deleted google.colab cell input and output -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">

<!-- Beginning of the deleted jupyter nbconvert --to html CaseStudy_MinimizeMisclassicationCost.ipynb
 cell input and output -->



<!-- End of the deleted jupyter nbconvert --to html CaseStudy_MinimizeMisclassicationCost.ipynb
 cell input and output -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">

<!-- Beginning of the deleted data = pd.read_csv(r"C:\\Users\\luisc\\Downloads\\final_project.csv") cell input; there was no output -->


<!-- End of the deleted data = pd.read_csv(r"C:\\Users\\luisc\\Downloads\\final_project.csv") cell input; there was no output -->
 
 
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">

<!-- Beginning of newly added comment explaining that I'm checking the shape of the dataset -->
<h2> Load In The Dataset And Check The Dimensions </h2>
<!-- End of newly added comment explaining that I'm checking the shape of the dataset -->

<!-- Beginning of data.shape cell, input and output -->

<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">data</span><span class="o">.</span><span class="n">shape</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>(160000, 51)</pre>
</div>
</div>
</div>
</div>
<!-- End of data.shape cell, input and output -->

</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1">## Ok so 51 columns and 160k rows</span>
<span class="c1">## Should isolate the y while I'm at it already</span>
<!-- Beginning of y = data.iloc[0:,-1] --><span class="n">y</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">data</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span><span class="mi">0</span><span class="p">:</span><span class="mi">50</span><span class="p">]</span> <!-- End of x = data.iloc[0:,0:50] -->
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">

<!-- Beginning of newly added comment explaining the consequences of wrongful predictions -->
<h2> Background Of Problem That Needs Solving </h2>
<!-- End of newly added comment explaining the consequences of wrongful predictions -->

<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1">## Ok so the thing here is</span>
<span class="c1">### predicting 1 when it's 0 costs us $100</span>
<span class="c1">### predicting 0 when it's 1 costs us $40</span>
<span class="c1">### If I make a mistake, I want to be doing false negatives (predict 0 but not 0) instead of false positives (predict 1 but not 1)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of deleted x.iloc[0:,0 ] cell, input and output -->

<!-- End of deleted x.iloc[0:,0 ] cell, input and output -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of x cell (which shows the x variables), input and output -->
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x0</th>
<th>x1</th>
<th>x2</th>
<th>x3</th>
<th>x4</th>
<th>x5</th>
<th>x6</th>
<th>x7</th>
<th>x8</th>
<th>x9</th>
<th>...</th>
<th>x40</th>
<th>x41</th>
<th>x42</th>
<th>x43</th>
<th>x44</th>
<th>x45</th>
<th>x46</th>
<th>x47</th>
<th>x48</th>
<th>x49</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>-0.166563</td>
<td>-3.961588</td>
<td>4.621113</td>
<td>2.481908</td>
<td>-1.800135</td>
<td>0.804684</td>
<td>6.718751</td>
<td>-14.789997</td>
<td>-1.040673</td>
<td>-4.204950</td>
<td>...</td>
<td>-10.612200</td>
<td>-1.497117</td>
<td>5.414063</td>
<td>-2.325655</td>
<td>1.674827</td>
<td>-0.264332</td>
<td>60.781427</td>
<td>-7.689696</td>
<td>0.151589</td>
<td>-8.040166</td>
</tr>
<tr>
<th>1</th>
<td>-0.149894</td>
<td>-0.585676</td>
<td>27.839856</td>
<td>4.152333</td>
<td>6.426802</td>
<td>-2.426943</td>
<td>40.477058</td>
<td>-6.725709</td>
<td>0.896421</td>
<td>0.330165</td>
<td>...</td>
<td>2.147427</td>
<td>36.292790</td>
<td>4.490915</td>
<td>0.762561</td>
<td>6.526662</td>
<td>1.007927</td>
<td>15.805696</td>
<td>-4.896678</td>
<td>-0.320283</td>
<td>16.719974</td>
</tr>
<tr>
<th>2</th>
<td>-0.321707</td>
<td>-1.429819</td>
<td>12.251561</td>
<td>6.586874</td>
<td>-5.304647</td>
<td>-11.311090</td>
<td>17.812850</td>
<td>11.060572</td>
<td>5.325880</td>
<td>-2.632984</td>
<td>...</td>
<td>-0.863137</td>
<td>-0.368491</td>
<td>9.088864</td>
<td>-0.689886</td>
<td>-2.731118</td>
<td>0.754200</td>
<td>30.856417</td>
<td>-7.428573</td>
<td>-2.090804</td>
<td>-7.869421</td>
</tr>
<tr>
<th>3</th>
<td>-0.245594</td>
<td>5.076677</td>
<td>-24.149632</td>
<td>3.637307</td>
<td>6.505811</td>
<td>2.290224</td>
<td>-35.111751</td>
<td>-18.913592</td>
<td>-0.337041</td>
<td>-5.568076</td>
<td>...</td>
<td>12.084421</td>
<td>15.691546</td>
<td>-7.467775</td>
<td>2.940789</td>
<td>-6.424112</td>
<td>0.419776</td>
<td>-72.424569</td>
<td>5.361375</td>
<td>1.806070</td>
<td>-7.670847</td>
</tr>
<tr>
<th>4</th>
<td>-0.273366</td>
<td>0.306326</td>
<td>-11.352593</td>
<td>1.676758</td>
<td>2.928441</td>
<td>-0.616824</td>
<td>-16.505817</td>
<td>27.532281</td>
<td>1.199715</td>
<td>-4.309105</td>
<td>...</td>
<td>30.004727</td>
<td>-13.911297</td>
<td>-5.229937</td>
<td>1.783928</td>
<td>3.957801</td>
<td>-0.096988</td>
<td>-14.085435</td>
<td>-0.208351</td>
<td>-0.894942</td>
<td>15.724742</td>
</tr>
<tr>
<th>...</th>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
</tr>
<tr>
<th>159995</th>
<td>-0.487024</td>
<td>-4.270269</td>
<td>0.417395</td>
<td>-1.992423</td>
<td>1.757552</td>
<td>-1.167819</td>
<td>0.606860</td>
<td>41.084463</td>
<td>-1.923188</td>
<td>-2.374213</td>
<td>...</td>
<td>-5.032652</td>
<td>-9.390451</td>
<td>8.096802</td>
<td>-0.875131</td>
<td>-1.413787</td>
<td>-0.363968</td>
<td>15.339392</td>
<td>4.364205</td>
<td>-3.831489</td>
<td>28.389858</td>
</tr>
<tr>
<th>159996</th>
<td>0.825477</td>
<td>4.804368</td>
<td>22.161535</td>
<td>11.371303</td>
<td>1.715901</td>
<td>6.990759</td>
<td>32.221207</td>
<td>-12.278038</td>
<td>-3.861086</td>
<td>6.715126</td>
<td>...</td>
<td>-8.472736</td>
<td>12.803189</td>
<td>0.841446</td>
<td>-0.682177</td>
<td>-5.047677</td>
<td>-0.017898</td>
<td>0.780130</td>
<td>6.387266</td>
<td>-1.374742</td>
<td>-1.623952</td>
</tr>
<tr>
<th>159997</th>
<td>-0.802489</td>
<td>5.362696</td>
<td>7.243419</td>
<td>-7.496074</td>
<td>2.295250</td>
<td>-2.756067</td>
<td>10.531388</td>
<td>42.515821</td>
<td>1.420984</td>
<td>6.788916</td>
<td>...</td>
<td>22.669070</td>
<td>-0.346570</td>
<td>-0.144098</td>
<td>0.738298</td>
<td>7.241041</td>
<td>0.215347</td>
<td>-12.155249</td>
<td>3.265263</td>
<td>1.230963</td>
<td>3.335471</td>
</tr>
<tr>
<th>159998</th>
<td>0.339237</td>
<td>7.609895</td>
<td>5.368414</td>
<td>-2.825481</td>
<td>4.046102</td>
<td>15.322603</td>
<td>7.805271</td>
<td>-10.233054</td>
<td>2.609986</td>
<td>4.251127</td>
<td>...</td>
<td>-32.356360</td>
<td>-0.307656</td>
<td>-0.601145</td>
<td>-3.443112</td>
<td>0.549931</td>
<td>0.206728</td>
<td>5.081980</td>
<td>1.701462</td>
<td>-0.279619</td>
<td>-1.986424</td>
</tr>
<tr>
<th>159999</th>
<td>-0.296748</td>
<td>-0.412773</td>
<td>-10.911407</td>
<td>-5.633629</td>
<td>-4.028154</td>
<td>15.939428</td>
<td>-15.864365</td>
<td>-46.388192</td>
<td>18.339472</td>
<td>-4.575499</td>
<td>...</td>
<td>-44.789367</td>
<td>27.837473</td>
<td>1.392395</td>
<td>0.893555</td>
<td>-1.848590</td>
<td>-0.423982</td>
<td>-17.379380</td>
<td>5.916490</td>
<td>-2.767444</td>
<td>15.547557</td>
</tr>
</tbody>
</table>
<p>160000 rows × 50 columns</p>
</div>
</div>
</div>
</div>
</div>
<!-- End of x cell (which shows the x variables), input and output -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of deleted x.iloc[:,31].unique() cell, input and output -->

<!-- End of deleted x.iloc[:,31].unique() cell, input and output -->

<!-- Beginning of newly added comment explaining that the variables have different issues -->
<h2> Create New Variables Based On Issue That Data Had </h2>
<!-- End of newly added comment explaining that the variables have different issues -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<!-- Beginning of cell that explains the differences and creates only_nums -->
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1"># Ok so x24, x29, and x30 are factors</span>
<span class="c1"># Ok x32 has a percentage at the end</span>
<span class="c1"># Ok x37 has a dollar sign at the beginnign</span>

<span class="n">only_nums</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span> <span class="nb">list</span><span class="p">(</span><span class="nb">range</span><span class="p">(</span><span class="mi">0</span><span class="p">,</span><span class="mi">24</span><span class="p">))</span> <span class="o">+</span> <span class="nb">list</span><span class="p">(</span><span class="nb">range</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span><span class="mi">29</span><span class="p">))</span> <span class="o">+</span> <span class="p">[</span><span class="mi">31</span><span class="p">]</span> <span class="o">+</span> <span class="nb">list</span><span class="p">(</span><span class="nb">range</span><span class="p">(</span><span class="mi">33</span><span class="p">,</span><span class="mi">37</span><span class="p">))</span> <span class="o">+</span> <span class="nb">list</span><span class="p">(</span><span class="nb">range</span><span class="p">(</span><span class="mi">38</span><span class="p">,</span><span class="mi">50</span><span class="p">))]</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<!-- End of cell that explains the differences and creates only_nums -->

<!-- Beginning of cell that creates only_categorical  -->
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">only_categorical</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span> <span class="p">[</span><span class="mi">24</span><span class="p">,</span><span class="mi">29</span><span class="p">,</span><span class="mi">30</span><span class="p">]]</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- End of cell that creates only_categorical  -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<!-- Beginning of cell that creates only_special_symbols  -->

<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">only_special_symbols</span><span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span> <span class="p">[</span><span class="mi">32</span><span class="p">,</span><span class="mi">37</span><span class="p">]]</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- End of cell that creates only_special_symbols  -->

<!-- Beginning of newly added comment that explains why I dropped the only_nums NAs -->
<h3> Very small number of NAs for only_nums so they will be dropped </h3>
<!-- End of newly added comment that explains why I dropped the only_nums NAs -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">only_nums</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x0</th>
<th>x1</th>
<th>x2</th>
<th>x3</th>
<th>x4</th>
<th>x5</th>
<th>x6</th>
<th>x7</th>
<th>x8</th>
<th>x9</th>
<th>...</th>
<th>x40</th>
<th>x41</th>
<th>x42</th>
<th>x43</th>
<th>x44</th>
<th>x45</th>
<th>x46</th>
<th>x47</th>
<th>x48</th>
<th>x49</th>
</tr>
</thead>
<tbody>
<tr>
<th>count</th>
<td>159974.000000</td>
<td>159975.000000</td>
<td>159962.000000</td>
<td>159963.000000</td>
<td>159974.000000</td>
<td>159963.000000</td>
<td>159974.000000</td>
<td>159973.000000</td>
<td>159979.000000</td>
<td>159970.000000</td>
<td>...</td>
<td>159964.000000</td>
<td>159960.000000</td>
<td>159974.000000</td>
<td>159963.000000</td>
<td>159960.000000</td>
<td>159971.000000</td>
<td>159969.000000</td>
<td>159963.000000</td>
<td>159968.000000</td>
<td>159968.000000</td>
</tr>
<tr>
<th>mean</th>
<td>-0.001028</td>
<td>0.001358</td>
<td>-1.150145</td>
<td>-0.024637</td>
<td>-0.000549</td>
<td>0.013582</td>
<td>-1.670670</td>
<td>-7.692795</td>
<td>-0.030540</td>
<td>0.005462</td>
<td>...</td>
<td>-2.316526</td>
<td>6.701076</td>
<td>-1.833820</td>
<td>-0.002091</td>
<td>-0.006250</td>
<td>0.000885</td>
<td>-12.755395</td>
<td>0.028622</td>
<td>-0.000224</td>
<td>-0.674224</td>
</tr>
<tr>
<th>std</th>
<td>0.371137</td>
<td>6.340632</td>
<td>13.273480</td>
<td>8.065032</td>
<td>6.382293</td>
<td>7.670076</td>
<td>19.298665</td>
<td>30.542264</td>
<td>8.901185</td>
<td>6.355040</td>
<td>...</td>
<td>17.043549</td>
<td>18.680196</td>
<td>5.110705</td>
<td>1.534952</td>
<td>4.164595</td>
<td>0.396621</td>
<td>36.608641</td>
<td>4.788157</td>
<td>1.935501</td>
<td>15.036738</td>
</tr>
<tr>
<th>min</th>
<td>-1.592635</td>
<td>-26.278302</td>
<td>-59.394048</td>
<td>-35.476594</td>
<td>-28.467536</td>
<td>-33.822988</td>
<td>-86.354483</td>
<td>-181.506976</td>
<td>-37.691045</td>
<td>-27.980659</td>
<td>...</td>
<td>-74.059196</td>
<td>-82.167224</td>
<td>-27.933750</td>
<td>-6.876234</td>
<td>-17.983487</td>
<td>-1.753221</td>
<td>-201.826828</td>
<td>-21.086333</td>
<td>-8.490155</td>
<td>-65.791191</td>
</tr>
<tr>
<th>25%</th>
<td>-0.251641</td>
<td>-4.260973</td>
<td>-10.166536</td>
<td>-5.454438</td>
<td>-4.313118</td>
<td>-5.148130</td>
<td>-14.780146</td>
<td>-27.324771</td>
<td>-6.031058</td>
<td>-4.260619</td>
<td>...</td>
<td>-13.953629</td>
<td>-5.804080</td>
<td>-5.162869</td>
<td>-1.039677</td>
<td>-2.812055</td>
<td>-0.266518</td>
<td>-36.428329</td>
<td>-3.216016</td>
<td>-1.320800</td>
<td>-10.931753</td>
</tr>
<tr>
<th>50%</th>
<td>-0.002047</td>
<td>0.004813</td>
<td>-1.340932</td>
<td>-0.031408</td>
<td>0.000857</td>
<td>0.014118</td>
<td>-1.948594</td>
<td>-6.956789</td>
<td>-0.016840</td>
<td>0.006045</td>
<td>...</td>
<td>-2.701867</td>
<td>6.840110</td>
<td>-1.923754</td>
<td>-0.004385</td>
<td>-0.010484</td>
<td>0.001645</td>
<td>-12.982497</td>
<td>0.035865</td>
<td>-0.011993</td>
<td>-0.574410</td>
</tr>
<tr>
<th>75%</th>
<td>0.248532</td>
<td>4.284220</td>
<td>7.871676</td>
<td>5.445179</td>
<td>4.306660</td>
<td>5.190749</td>
<td>11.446931</td>
<td>12.217071</td>
<td>5.972349</td>
<td>4.305734</td>
<td>...</td>
<td>8.981616</td>
<td>19.266367</td>
<td>1.453507</td>
<td>1.033275</td>
<td>2.783274</td>
<td>0.269049</td>
<td>11.445443</td>
<td>3.268028</td>
<td>1.317703</td>
<td>9.651072</td>
</tr>
<tr>
<th>max</th>
<td>1.600849</td>
<td>27.988178</td>
<td>63.545653</td>
<td>38.906025</td>
<td>26.247812</td>
<td>35.550110</td>
<td>92.390605</td>
<td>149.150634</td>
<td>39.049831</td>
<td>27.377842</td>
<td>...</td>
<td>88.824477</td>
<td>100.050432</td>
<td>22.668041</td>
<td>6.680922</td>
<td>19.069759</td>
<td>1.669205</td>
<td>150.859415</td>
<td>20.836854</td>
<td>8.226552</td>
<td>66.877604</td>
</tr>
</tbody>
</table>
<p>8 rows × 45 columns</p>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">drop_num_nas</span> <span class="o">=</span> <span class="n">only_nums</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added comment that explains why I dropped the only_nums NAs -->
<h3> Very small number of NAs for only_categorical so they will be dropped </h3>
<!-- End of newly added comment that explains why I dropped the only_nums NAs -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">only_categorical</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x24</th>
<th>x29</th>
<th>x30</th>
</tr>
</thead>
<tbody>
<tr>
<th>count</th>
<td>159972</td>
<td>159970</td>
<td>159970</td>
</tr>
<tr>
<th>unique</th>
<td>3</td>
<td>12</td>
<td>5</td>
</tr>
<tr>
<th>top</th>
<td>asia</td>
<td>July</td>
<td>wednesday</td>
</tr>
<tr>
<th>freq</th>
<td>138965</td>
<td>45569</td>
<td>101535</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">drop_cat_nas</span> <span class="o">=</span> <span class="n">only_categorical</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added comment that explains why I dropped the only_nums NAs -->
<h3> Very small number of NAs for only_categorical so they will be dropped </h3>
<!-- End of newly added comment that explains why I dropped the only_nums NAs -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">only_special_symbols</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x32</th>
<th>x37</th>
</tr>
</thead>
<tbody>
<tr>
<th>count</th>
<td>159969</td>
<td>159977</td>
</tr>
<tr>
<th>unique</th>
<td>12</td>
<td>129198</td>
</tr>
<tr>
<th>top</th>
<td>0.01%</td>
<td>$-311.26</td>
</tr>
<tr>
<th>freq</th>
<td>40767</td>
<td>6</td>
</tr>
</tbody>
</table>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">drop_spesym_nas</span> <span class="o">=</span> <span class="n">only_special_symbols</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of the deleted x['x32'] cell, input and ouput -->

<!-- Beginning of the deleted x['x32'] cell, input and ouput -->

<!-- Beginning of newly added comment that explains why I dropped the NAs -->
<h3> Drop the NAs from the original x variable now that we know there's no harm </h3>
<!-- End of newly added comment that explains why I dropped the NAs -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">dropna</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added comment that explains that I'll be transforming the categorical variables -->
<h2> Transform The Variables That Are Not Numeric </h2>
<!-- End of newly added comment that explains that I'll be transforming the categorical variables -->

<!-- Beginning of newly added comment that explains how I'll deal with x37 -->
<h3> Reassign x37 to everything except the first character since the dollar sign is always the first character</h3>
<!-- End of newly added comment that explains how I'll deal with x37 -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span><span class="mi">37</span><span class="p">]</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>0          $1313.96
1          $1962.78
2           $430.47
3         $-2366.29
4          $-620.66
            ...    
159995     $-891.96
159996     $1588.65
159997      $687.46
159998      $439.21
159999    $-1229.34
Name: x37, Length: 158392, dtype: object</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x37'</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="n">a</span><span class="p">[</span><span class="mi">1</span><span class="p">:]</span> <span class="k">for</span> <span class="n">a</span> <span class="ow">in</span> <span class="n">x</span><span class="p">[</span><span class="s1">'x37'</span><span class="p">]]</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x37'</span><span class="p">]</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>0          1313.96
1          1962.78
2           430.47
3         -2366.29
4          -620.66
            ...   
159995     -891.96
159996     1588.65
159997      687.46
159998      439.21
159999    -1229.34
Name: x37, Length: 158392, dtype: object</pre>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added comment that explains how I'll deal with x32 -->
<h3> Reassign x32 to everything except the last character since the percent sign is always the last character</h3>
<!-- End of newly added comment that explains how I'll deal with x32  -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x32'</span><span class="p">]</span> <span class="o">=</span> <span class="p">[</span><span class="n">a</span><span class="p">[</span><span class="mi">0</span><span class="p">:</span><span class="o">-</span><span class="mi">1</span><span class="p">]</span> <span class="k">for</span> <span class="n">a</span> <span class="ow">in</span> <span class="n">x</span><span class="p">[</span><span class="s1">'x32'</span><span class="p">]]</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x32'</span><span class="p">]</span> <span class="o">=</span> <span class="n">x</span><span class="p">[</span><span class="s1">'x32'</span><span class="p">]</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="s1">'float'</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of deleted cell that has two comments # x24	x29	x30 were categorical -->

<!-- End of deleted cell that has two comments # x24	x29	x30 were categorical -->
<!-- Beginning of newly added comment that explains how I'll deal with x32 -->
<h3> Check how many unique entries the categorical variables have before one-hot encoding </h3>
<!-- End of newly added comment that explains how I'll deal with x32  -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x24'</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>array(['euorpe', 'asia', 'america'], dtype=object)</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x29'</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>array(['July', 'Aug', 'Jun', 'May', 'sept.', 'Apr', 'Nov', 'Oct', 'Mar',
       'Feb', 'Dev', 'January'], dtype=object)</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="p">[</span><span class="s1">'x30'</span><span class="p">]</span><span class="o">.</span><span class="n">unique</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>array(['tuesday', 'wednesday', 'thurday', 'monday', 'friday'],
      dtype=object)</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<!-- Beginning of deleted failsafe = x cell, only had input-->

<!-- End of deleted failsafe = x cell, only had input-->

<!-- Beginning of newly added comment explaining why I'll dummy encode-->
<h3> There is not that many unique entries so not many columns will be added, I'll one-hot encode them all then </h3>
<!-- End of newly added comment explaining why I'll dummy encode-->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1"># Get one hot encoding of columns B</span>
<span class="n">one_hot</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">get_dummies</span><span class="p">(</span><span class="n">x</span><span class="o">.</span><span class="n">iloc</span><span class="p">[</span><span class="mi">0</span><span class="p">:,</span> <span class="p">[</span><span class="mi">24</span><span class="p">,</span><span class="mi">29</span><span class="p">,</span><span class="mi">30</span><span class="p">]])</span>
<span class="c1"># Drop column B as it is now enco#ded</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">'x24'</span><span class="p">,</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">'x29'</span><span class="p">,</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">'x30'</span><span class="p">,</span><span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="c1"># Join the encoded df</span>
<span class="n">x</span> <span class="o">=</span> <span class="n">x</span><span class="o">.</span><span class="n">join</span><span class="p">(</span><span class="n">one_hot</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x0</th>
<th>x1</th>
<th>x2</th>
<th>x3</th>
<th>x4</th>
<th>x5</th>
<th>x6</th>
<th>x7</th>
<th>x8</th>
<th>x9</th>
<th>...</th>
<th>x29_Mar</th>
<th>x29_May</th>
<th>x29_Nov</th>
<th>x29_Oct</th>
<th>x29_sept.</th>
<th>x30_friday</th>
<th>x30_monday</th>
<th>x30_thurday</th>
<th>x30_tuesday</th>
<th>x30_wednesday</th>
</tr>
</thead>
<tbody>
<tr>
<th>0</th>
<td>-0.166563</td>
<td>-3.961588</td>
<td>4.621113</td>
<td>2.481908</td>
<td>-1.800135</td>
<td>0.804684</td>
<td>6.718751</td>
<td>-14.789997</td>
<td>-1.040673</td>
<td>-4.204950</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
<td>False</td>
</tr>
<tr>
<th>1</th>
<td>-0.149894</td>
<td>-0.585676</td>
<td>27.839856</td>
<td>4.152333</td>
<td>6.426802</td>
<td>-2.426943</td>
<td>40.477058</td>
<td>-6.725709</td>
<td>0.896421</td>
<td>0.330165</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>2</th>
<td>-0.321707</td>
<td>-1.429819</td>
<td>12.251561</td>
<td>6.586874</td>
<td>-5.304647</td>
<td>-11.311090</td>
<td>17.812850</td>
<td>11.060572</td>
<td>5.325880</td>
<td>-2.632984</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>3</th>
<td>-0.245594</td>
<td>5.076677</td>
<td>-24.149632</td>
<td>3.637307</td>
<td>6.505811</td>
<td>2.290224</td>
<td>-35.111751</td>
<td>-18.913592</td>
<td>-0.337041</td>
<td>-5.568076</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>4</th>
<td>-0.273366</td>
<td>0.306326</td>
<td>-11.352593</td>
<td>1.676758</td>
<td>2.928441</td>
<td>-0.616824</td>
<td>-16.505817</td>
<td>27.532281</td>
<td>1.199715</td>
<td>-4.309105</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
<td>False</td>
</tr>
<tr>
<th>...</th>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
<td>...</td>
</tr>
<tr>
<th>159995</th>
<td>-0.487024</td>
<td>-4.270269</td>
<td>0.417395</td>
<td>-1.992423</td>
<td>1.757552</td>
<td>-1.167819</td>
<td>0.606860</td>
<td>41.084463</td>
<td>-1.923188</td>
<td>-2.374213</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>159996</th>
<td>0.825477</td>
<td>4.804368</td>
<td>22.161535</td>
<td>11.371303</td>
<td>1.715901</td>
<td>6.990759</td>
<td>32.221207</td>
<td>-12.278038</td>
<td>-3.861086</td>
<td>6.715126</td>
<td>...</td>
<td>False</td>
<td>True</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>159997</th>
<td>-0.802489</td>
<td>5.362696</td>
<td>7.243419</td>
<td>-7.496074</td>
<td>2.295250</td>
<td>-2.756067</td>
<td>10.531388</td>
<td>42.515821</td>
<td>1.420984</td>
<td>6.788916</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>159998</th>
<td>0.339237</td>
<td>7.609895</td>
<td>5.368414</td>
<td>-2.825481</td>
<td>4.046102</td>
<td>15.322603</td>
<td>7.805271</td>
<td>-10.233054</td>
<td>2.609986</td>
<td>4.251127</td>
<td>...</td>
<td>False</td>
<td>True</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
</tr>
<tr>
<th>159999</th>
<td>-0.296748</td>
<td>-0.412773</td>
<td>-10.911407</td>
<td>-5.633629</td>
<td>-4.028154</td>
<td>15.939428</td>
<td>-15.864365</td>
<td>-46.388192</td>
<td>18.339472</td>
<td>-4.575499</td>
<td>...</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>False</td>
<td>True</td>
<td>False</td>
</tr>
</tbody>
</table>
<p>158392 rows × 67 columns</p>
</div>
</div>
</div>
</div>
</div>

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of deleted duplicate x (had to back to back cells that just showed x), input and output-->


<!-- End of deleted duplicate x (had to back to back cells that just showed x), input and output-->

<!-- Beginning of deleted duplicate x (had to back to back cells that just showed x), input and output-->
<h2> Data Ready To Be Scaled Now</h2>
<!-- End of deleted duplicate x (had to back to back cells that just showed x), input and output-->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">x</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedHTMLCommon jp-RenderedHTML jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/html" tabindex="0">
<div>
<style scoped="">
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
<thead>
<tr style="text-align: right;">
<th></th>
<th>x0</th>
<th>x1</th>
<th>x2</th>
<th>x3</th>
<th>x4</th>
<th>x5</th>
<th>x6</th>
<th>x7</th>
<th>x8</th>
<th>x9</th>
<th>...</th>
<th>x40</th>
<th>x41</th>
<th>x42</th>
<th>x43</th>
<th>x44</th>
<th>x45</th>
<th>x46</th>
<th>x47</th>
<th>x48</th>
<th>x49</th>
</tr>
</thead>
<tbody>
<tr>
<th>count</th>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>...</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
<td>158392.000000</td>
</tr>
<tr>
<th>mean</th>
<td>-0.000808</td>
<td>0.003705</td>
<td>-1.148314</td>
<td>-0.023012</td>
<td>-0.000266</td>
<td>0.013282</td>
<td>-1.669562</td>
<td>-7.697877</td>
<td>-0.028853</td>
<td>0.004320</td>
<td>...</td>
<td>-2.318750</td>
<td>6.706030</td>
<td>-1.832959</td>
<td>-0.002174</td>
<td>-0.007254</td>
<td>0.000996</td>
<td>-12.751993</td>
<td>0.028262</td>
<td>0.000160</td>
<td>-0.672052</td>
</tr>
<tr>
<th>std</th>
<td>0.371064</td>
<td>6.340297</td>
<td>13.274738</td>
<td>8.066624</td>
<td>6.383306</td>
<td>7.672102</td>
<td>19.300472</td>
<td>30.541562</td>
<td>8.904048</td>
<td>6.354359</td>
<td>...</td>
<td>17.040216</td>
<td>18.675642</td>
<td>5.110079</td>
<td>1.535282</td>
<td>4.163766</td>
<td>0.396604</td>
<td>36.608634</td>
<td>4.787974</td>
<td>1.935087</td>
<td>15.033134</td>
</tr>
<tr>
<th>min</th>
<td>-1.592635</td>
<td>-26.278302</td>
<td>-59.394048</td>
<td>-33.864827</td>
<td>-28.467536</td>
<td>-33.822988</td>
<td>-86.354483</td>
<td>-181.506976</td>
<td>-37.691045</td>
<td>-27.980659</td>
<td>...</td>
<td>-74.059196</td>
<td>-82.167224</td>
<td>-27.933750</td>
<td>-6.876234</td>
<td>-17.983487</td>
<td>-1.753221</td>
<td>-201.826828</td>
<td>-21.086333</td>
<td>-8.490155</td>
<td>-65.791191</td>
</tr>
<tr>
<th>25%</th>
<td>-0.251246</td>
<td>-4.259016</td>
<td>-10.166609</td>
<td>-5.453044</td>
<td>-4.313987</td>
<td>-5.152419</td>
<td>-14.781485</td>
<td>-27.315875</td>
<td>-6.034094</td>
<td>-4.260304</td>
<td>...</td>
<td>-13.952620</td>
<td>-5.802178</td>
<td>-5.159340</td>
<td>-1.039992</td>
<td>-2.814168</td>
<td>-0.266369</td>
<td>-36.432779</td>
<td>-3.216974</td>
<td>-1.320800</td>
<td>-10.929046</td>
</tr>
<tr>
<th>50%</th>
<td>-0.001818</td>
<td>0.010023</td>
<td>-1.342199</td>
<td>-0.028470</td>
<td>-0.001138</td>
<td>0.015135</td>
<td>-1.951457</td>
<td>-6.959275</td>
<td>-0.016173</td>
<td>0.003098</td>
<td>...</td>
<td>-2.709284</td>
<td>6.847926</td>
<td>-1.922935</td>
<td>-0.004279</td>
<td>-0.012278</td>
<td>0.001841</td>
<td>-12.975088</td>
<td>0.036234</td>
<td>-0.011800</td>
<td>-0.569139</td>
</tr>
<tr>
<th>75%</th>
<td>0.248622</td>
<td>4.286606</td>
<td>7.878130</td>
<td>5.448332</td>
<td>4.308644</td>
<td>5.191172</td>
<td>11.454209</td>
<td>12.215119</td>
<td>5.978646</td>
<td>4.303807</td>
<td>...</td>
<td>8.972837</td>
<td>19.269855</td>
<td>1.452018</td>
<td>1.033870</td>
<td>2.781096</td>
<td>0.269194</td>
<td>11.445524</td>
<td>3.269134</td>
<td>1.318161</td>
<td>9.649839</td>
</tr>
<tr>
<th>max</th>
<td>1.600849</td>
<td>27.988178</td>
<td>63.545653</td>
<td>38.906025</td>
<td>26.247812</td>
<td>35.550110</td>
<td>92.390605</td>
<td>149.150634</td>
<td>39.049831</td>
<td>27.377842</td>
<td>...</td>
<td>88.824477</td>
<td>100.050432</td>
<td>22.668041</td>
<td>6.680922</td>
<td>19.069759</td>
<td>1.669205</td>
<td>150.859415</td>
<td>20.836854</td>
<td>8.226552</td>
<td>66.877604</td>
</tr>
</tbody>
</table>
<p>8 rows × 46 columns</p>
</div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">scaler</span> <span class="o">=</span> <span class="n">MinMaxScaler</span><span class="p">()</span>
<span class="n">scaled_x</span> <span class="o">=</span> <span class="n">scaler</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">x</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">scaled_x</span><span class="o">.</span><span class="n">shape</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>(158392, 67)</pre>
</div>
</div>
</div>
</div>
<!-- I'm at 'Run a logistic regression model to see how it performs' -->
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Run-a-logistic-regression-model-to-see-how-it-performs">Run a logistic regression model to see how it performs<a class="anchor-link" href="#Run-a-logistic-regression-model-to-see-how-it-performs">¶</a></h2>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">y</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">data</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="s1">'x0'</span><span class="p">,</span> <span class="n">how</span><span class="o">=</span><span class="s1">'inner'</span><span class="p">)</span><span class="o">.</span><span class="n">y</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">train_test_split</span>

<span class="n">X_train</span><span class="p">,</span> <span class="n">X_test</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">y_test</span> <span class="o">=</span> <span class="n">train_test_split</span><span class="p">(</span><span class="n">scaled_x</span><span class="p">,</span> <span class="n">y</span><span class="o">.</span><span class="n">astype</span><span class="p">(</span><span class="s1">'int'</span><span class="p">),</span> <span class="n">test_size</span><span class="o">=</span><span class="mf">0.2</span><span class="p">,</span> <span class="n">random_state</span><span class="o">=</span><span class="mi">42</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="kn">import</span> <span class="n">LogisticRegression</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="kn">import</span> <span class="n">cross_val_score</span>

<span class="c1"># Do Logistic Regression to find the missing payer_code</span>
<span class="n">log_model</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">()</span>
<span class="n">crossval_scores_payer_code</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">log_model</span><span class="p">,</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">scoring</span> <span class="o">=</span> <span class="s1">'accuracy'</span><span class="p">)</span> <span class="c1"># Around 70% or so, okok</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">log_model</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">()</span>
<span class="n">log_model_fit</span> <span class="o">=</span> <span class="n">log_model</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">preds_log</span> <span class="o">=</span> <span class="n">log_model</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">accuracy_score</span><span class="p">(</span><span class="n">preds_log</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>0.7037153950566621</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span><span class="p">,</span> <span class="n">ConfusionMatrixDisplay</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">preds_log</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
<span class="n">disp</span> <span class="o">=</span> <span class="n">ConfusionMatrixDisplay</span><span class="p">(</span><span class="n">confusion_matrix</span><span class="o">=</span><span class="n">cm</span><span class="p">)</span>
<span class="n">disp</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAgwAAAGwCAYAAADFZj2cAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjguMywgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/H5lhTAAAACXBIWXMAAA9hAAAPYQGoP6dpAABFqUlEQVR4nO3de1hU1foH8O8MOIDADKABTiJi5t3QtDhY3o4kXo5JWh2Vkoz0V4l5y7SL5KWkNG+oR9JSs4OpXeR4SyUs8UIoKKmEKImKyoCGMIJym9m/P4hdE+ow7EEu+/t5nv08zt5rrb22Dzov6117LYUgCAKIiIiI7kFZ1x0gIiKi+o8BAxEREZnFgIGIiIjMYsBAREREZjFgICIiIrMYMBAREZFZDBiIiIjILNu67oAURqMRV69ehbOzMxQKRV13h4iILCQIAm7evAmtVgulsvZ+hy0uLkZpaankdlQqFezt7a3Qo4anQQcMV69ehZeXV113g4iIJMrKykLLli1rpe3i4mL4eDtBl2uQ3JanpycyMzNlGTQ06IDB2dkZAHDxeGuonZhdocZp6Otj67oLRLWmvLwYR3/6SPz/vDaUlpZCl2vAxeTWUDvX/LtCf9MI7x4XUFpayoChoalMQ6idlJJ+CIjqM1tb+f3HRPJzP9LKTs4KODnX/D5GyDv13aADBiIiouoyCEYYJOyeZBCM1utMA8SAgYiIZMEIAUbUPGKQUrcx4Dg+ERERmcURBiIikgUjjJCSVJBWu+FjwEBERLJgEAQYhJqnFaTUbQyYkiAiIiKzOMJARESywEmP0jBgICIiWTBCgIEBQ40xJUFERERmcYSBiIhkgSkJaRgwEBGRLPAtCWmYkiAiIiKzOMJARESyYPzjkFJfzhgwEBGRLBgkviUhpW5jwICBiIhkwSBA4m6V1utLQ8Q5DERERGQWRxiIiEgWOIdBGgYMREQkC0YoYIBCUn05Y0qCiIiIzOIIAxERyYJRqDik1JczBgxERCQLBokpCSl1GwOmJIiIiMgsjjAQEZEscIRBGgYMREQkC0ZBAaMg4S0JCXUbA6YkiIiIyCyOMBARkSwwJSENAwYiIpIFA5QwSBhYN1ixLw0RAwYiIpIFQeIcBoFzGIiIiIjujSMMREQkC5zDIA0DBiIikgWDoIRBkDCHQeZLQzMlQURERGZxhIGIiGTBCAWMEn5PNkLeQwwMGIiISBY4h0EapiSIiIjILI4wEBGRLEif9MiUBBERUaNXMYdBwuZTTEkQERER3RtHGIiISBaMEveS4FsSREREMsA5DNIwYCAiIlkwQsl1GCTgHAYiIiIyiyMMREQkCwZBAYOELaql1G0MGDAQEZEsGCROejQwJUFERER0bwwYiIhIFoyCUvJhifj4eAwbNgxarRYKhQIxMTF3Lfvqq69CoVBg2bJlJufz8vIQHBwMtVoNFxcXhIaGorCw0KTMyZMn0bt3b9jb28PLywsLFy6s0v7XX3+NDh06wN7eHl27dsXu3bstehaAAQMREclEZUpCymGJoqIi+Pr6YtWqVfcst23bNvz888/QarVVrgUHByM1NRWxsbHYuXMn4uPjMWHCBPG6Xq/HwIED4e3tjeTkZCxatAhz5szBmjVrxDJHjhzB6NGjERoaihMnTiAoKAhBQUE4ffq0Rc/DOQxERES1YPDgwRg8ePA9y1y5cgWTJk3C3r17MXToUJNraWlp2LNnD44dO4aePXsCAFasWIEhQ4bgk08+gVarRXR0NEpLS7Fu3TqoVCp07twZKSkpWLJkiRhYLF++HIMGDcKMGTMAAPPnz0dsbCxWrlyJqKioaj8PRxiIiEgWjPjzTYmaHMY/2tHr9SZHSUlJzfpjNOLFF1/EjBkz0Llz5yrXExIS4OLiIgYLABAQEAClUonExESxTJ8+faBSqcQygYGBSE9Px40bN8QyAQEBJm0HBgYiISHBov4yYCAiIlmoXLhJygEAXl5e0Gg04hEREVGj/nz88cewtbXFG2+8ccfrOp0O7u7uJudsbW3h5uYGnU4nlvHw8DApU/nZXJnK69XFlAQREZEFsrKyoFarxc92dnYWt5GcnIzly5fj+PHjUCgaxvoOHGEgIiJZqNxLQsoBAGq12uSoScBw8OBB5ObmolWrVrC1tYWtrS0uXryI6dOno3Xr1gAAT09P5ObmmtQrLy9HXl4ePD09xTI5OTkmZSo/mytTeb26GDAQEZEsGKGQfFjLiy++iJMnTyIlJUU8tFotZsyYgb179wIA/P39kZ+fj+TkZLHe/v37YTQa4efnJ5aJj49HWVmZWCY2Nhbt27eHq6urWCYuLs7k/rGxsfD397eoz0xJEBGRLEjfrdKyuoWFhcjIyBA/Z2ZmIiUlBW5ubmjVqhWaNWtmUr5Jkybw9PRE+/btAQAdO3bEoEGDMH78eERFRaGsrAxhYWEYNWqU+ArmmDFjMHfuXISGhmLmzJk4ffo0li9fjqVLl4rtTp48GX379sXixYsxdOhQbN68GUlJSSavXlYHRxiIiIhqQVJSErp3747u3bsDAKZNm4bu3bsjPDy82m1ER0ejQ4cOGDBgAIYMGYInn3zS5Iteo9Fg3759yMzMRI8ePTB9+nSEh4ebrNXQq1cvbNq0CWvWrIGvry+++eYbxMTEoEuXLhY9D0cYiIhIFqTvJWFZ3X79+kEQqr//xIULF6qcc3Nzw6ZNm+5Z75FHHsHBgwfvWea5557Dc889V+2+3AkDBiIikgWjoIBRwo6TUuo2BkxJEBERkVkcYSAiIlkwSkxJGGX+OzYDBiIikoWa7Dj59/pyJu+nJyIiomrhCAMREcmCAQoYJCy+JKVuY8CAgYiIZIEpCWnk/fRERERULRxhICIiWTBAWlrBYL2uNEgMGIiISBaYkpCGAQMREcnC/d58qrGR99MTERFRtXCEgYiIZEGAAkYJcxgEvlZJRETU+DElIY28n56IiIiqhSMMREQkC9zeWhoGDEREJAsGibtVSqnbGMj76YmIiKhaOMJARESywJSENAwYiIhIFoxQwihhYF1K3cZA3k9PRERE1cIRBiIikgWDoIBBQlpBSt3GgAEDERHJAucwSMOAgYiIZEGQuFulwJUeiYiIiO6NIwxERCQLBihgkLCBlJS6jQEDBiIikgWjIG0eglGwYmcaIKYkiIiIyCyOMDRyp352xNf/cce5U02Rl9ME73+eiV6DC8Trn0xphditbiZ1evTTY8Gm8wCAX4444a1n296x7cjd6Wjf7TayMuwQOaslLp21R9FNGzTzKEP/Z27ghWk62DapKHtotwabIz1w9YIdysuAB31KMfLVXAQ8e6N2HpxkrblLESY8fwyPd70Me1U5ruSq8fHnvXH2wgN/lBAwLug4hvZNh1PTUpw+54GlX/bClRwNAMCj2U2MfToF3TtehZvmNq7nN8UPCW3x3x2+KDfYAAC8PPMxdewReGtvwKlpGa7faIq4xDb44n+PwmDg72L1kVHipEcpdRsDBgyNXPEtJdp0vo3A0XmYF+pzxzI9++sxfekl8XMT1Z/jbp16FuGrlNMm5b9Y2AIph5zQzvc2AMC2iYCAZ2+gbddbcNIYcD7VActmeMFoVODlt7MBAM4uBoyenAOvtsWwbSIg8Qc1Fk9tBZfm5ejZ76a1H5tkzKlpCVa8uxMn0lpg1pJA5N+0R0uPAhQW2YllRg05iRFP/YqPPuuD7GvOeHlEMhZO24uX3h2BsnJbtGpRAIVCwJIvnsCVXDV8HryB6S8dgr1dGaK2+AEAyg1K7DvSFucuNkPhLRUe8srD9JcOQakAPvu2Z109Pt2DEQoYJcxDkFK3MagXAcOqVauwaNEi6HQ6+Pr6YsWKFXj88cfruluNwmP/vInH/nnvL+QmKgFu7uXVulZeBiTsVWP4y9eh+OPfTgvvUrTwzhPLeLQsw8mEGzid6Cie8+1VaNLuM69cxw9b3ZB61JEBA1nV6CEnkZvniIXr+ojndNed/1JCwLNPpeLLHd1w+IQ3ACBibV98t3wTnnz0In48+hCOnW6JY6dbijWyr6nhtacAT/c/IwYM2dfUyL6mFsvk/O6Mbj9no2s7Xe0+IFEdqfPxlS1btmDatGl4//33cfz4cfj6+iIwMBC5ubl13TXZOJnghOe7dkbokx0QOasl9Hk2dy2bsE+DmzdsMfDfeXctcyVThaQf1XjEv/CO1wUBOHHQCVm/2aGL353LENVUr26XkJ7ZHO+/HofvlkdjzZxtGNrnjHi9xQM30czlNpJTteK5otsqpP32ADq3vfv/O45NS3HzL6MUf6d11+OxLlfwS7qndR6ErK5ypUcph5zV+QjDkiVLMH78eIwbNw4AEBUVhV27dmHdunWYNWtWHfeu8evZT48nBufDs1Upsi/YYf1HLfDuC22wbMc52Nwhbtj7VTP06HcTD2jLqlybMuxhZJx2QFmJEkNeuI6xM0x/0yrSKzHm0c4oK1VCaSNg0oLL6NGXAQNZl9b9Job/8wy+3tsF0Tt90cHnOiYF/4xygw32Hn4YbpqKVNoNvYNJvRt6B/Fa1Tb1eGbAr4jaUnXkc8W7O9DO+3eomhiw46f2WL+th/UfiqyCcxikqdOAobS0FMnJyXj77bfFc0qlEgEBAUhISKhSvqSkBCUlJeJnvV5/X/rZmPULyhf/7NOxGD6dbuMl/044ecQJ3Xubfplfu9oEyT85451PL9yxrXeiLuB2kRLnUx3w2QdafLPaHc9P/PM3NgcnI/4Tm47iIhucOOSET+c+CE/v0irpCiIpFAoB6Reai/MIMi41h8+DNzCsXxr2Hn7Y4vaauxRh4bQ9OJDkg13xHapcn7e6P5ral+Ehrzy8+vxR/HvQKWz+/hHJz0FU39RpwHD9+nUYDAZ4eHiYnPfw8MCZM2eqlI+IiMDcuXPvV/dkqYV3KTRu5bh6wa5KwLBvixucXcvhP7DgjnXdH6wYdfBuVwKjUYHlM7ww8tVccaRCqax4OwIAHupyG1nn7LFlhTsDBrKq3/MdcPGqi8m5i9ku6N3zAgAgr6BiZMFVfRt5BU3FMq7q28jIMn1jqJlLEZbM3I3UDA8s3vDkHe93Lc+p4h5XXaFUCpgecghb93SR/W+j9ZEREveSkPmkxwb1E/3222+joKBAPLKysuq6S43OtatNoL9hAzd305SDIFQEDAHP3hBflbwXoxEoL1dAMN67TFlpg/oRpAYgNcMDXp6mQW1LjwLk/F7xxZ59zRm/5zvg0U5XxetN7UvR8aFrSM1wF881dynC0pm7cfZCc3z8eW8I1fiiUSoE2NoYoeCPdb0k/PGWRE0PQeYBQ52OMDRv3hw2NjbIyckxOZ+TkwNPz6oTh+zs7GBnd/dJR1TV7SIlrmb++Xemy1Lht9MOcHYph7OrAf9d7Iknh+bD1b0c2RdU+OwDLbQ+JejxtzcXUg45QXfJDoPG/F7lHvu/c4WNrQCfjrfRRCXg7C9NsT6iBfo+/WdwsXmFOx5+5Ba0rUtRVqrA0Tg14r51w6QIBn1kXV/v64KV7+xA8NAU/HisDTq2uYZ/9UvHkg1P/FFCgW9iO+PFYSm4kqNG9nVnvPxMMq7faIpDxyvemmjuUoSls3Yj57oTorY8Do1zsdj+DX3FqETAPzJQblDi/GU3lJUr0b71dbzybBJ+PNaG6zDUU9ytUpo6DRhUKhV69OiBuLg4BAUFAQCMRiPi4uIQFhZWl11rNM7+0tRk4aVP5zwIAHjq+TxMishCZpo9Yr/2QZHeBs08yvFoXz1C3tJBZWe6Buqer5qhU89CtHq4BH+ntBGwdZU7rpy3gyAA7i1L8fS46xgx/ppYpviWEivf8cL17CZQ2Rvh9VAJ3lpxEf2G59fOg5NspWc+gNkrAzD+2SSMHZ6C7GtOWLXJDz/8/Oe/g827H4GDqhzTXzoMp6alOHXWAzOXBKKsvOK/xB6dr6Clhx4tPfT4eulmk/b7jwsFABiMSowechItPfRQKATk/O6EmLhO+Hpv5/v3sET3kUIQhDpdHXvLli0ICQnBp59+iscffxzLli3D1q1bcebMmSpzG/5Or9dDo9Hgxtk2UDszoqfGqf+4V+q6C0S1pry8GEd+mIOCggKo1WrzFWqg8rvimdhxaOKoqnE7ZUWl2PbU+lrta31W569V/vvf/8a1a9cQHh4OnU6Hbt26Yc+ePWaDBSIiIkswJSFNnQcMABAWFsYUBBERUT1WLwIGIiKi2sa9JKRhwEBERLLAlIQ0nClIREREZnGEgYiIZIEjDNIwYCAiIllgwCANUxJERERkFkcYiIhIFjjCIA0DBiIikgUB0l6NrNNlkesBpiSIiEgWKkcYpByWiI+Px7Bhw6DVaqFQKBATEyNeKysrw8yZM9G1a1c4OjpCq9Vi7NixuHr1qkkbeXl5CA4OhlqthouLC0JDQ1FYWGhS5uTJk+jduzfs7e3h5eWFhQsXVunL119/jQ4dOsDe3h5du3bF7t27LXoWgAEDERFRrSgqKoKvry9WrVpV5dqtW7dw/PhxzJ49G8ePH8d3332H9PR0PP300yblgoODkZqaitjYWOzcuRPx8fGYMGGCeF2v12PgwIHw9vZGcnIyFi1ahDlz5mDNmjVimSNHjmD06NEIDQ3FiRMnEBQUhKCgIJw+fdqi56nzzaek4OZTJAfcfIoas/u5+VS/na/B1tGuxu2UF5Xgp3+trlFfFQoFtm3bJu7MfCfHjh3D448/josXL6JVq1ZIS0tDp06dcOzYMfTs2RMAsGfPHgwZMgSXL1+GVqvF6tWr8e6770Kn00GlqthYa9asWYiJicGZM2cAVOzZVFRUhJ07d4r3+sc//oFu3bohKiqq2s/Ab1kiIpIFa6Uk9Hq9yVFSUmKV/hUUFEChUMDFxQUAkJCQABcXFzFYAICAgAAolUokJiaKZfr06SMGCwAQGBiI9PR03LhxQywTEBBgcq/AwEAkJCRY1D8GDERERBbw8vKCRqMRj4iICMltFhcXY+bMmRg9erQ4eqHT6eDu7m5SztbWFm5ubtDpdGKZv+/uXPnZXJnK69XFtySIiEgWrPVaZVZWlklKws6u5mkOoGIC5PPPPw9BELB69WpJbdUmBgxERCQLgqCAICFgqKyrVqutNt+iMli4ePEi9u/fb9Kup6cncnNzTcqXl5cjLy8Pnp6eYpmcnByTMpWfzZWpvF5dTEkQERHVgcpg4dy5c/jhhx/QrFkzk+v+/v7Iz89HcnKyeG7//v0wGo3w8/MTy8THx6OsrEwsExsbi/bt28PV1VUsExcXZ9J2bGws/P39LeovAwYiIpIFIxSSD0sUFhYiJSUFKSkpAIDMzEykpKTg0qVLKCsrw7PPPoukpCRER0fDYDBAp9NBp9OhtLQUANCxY0cMGjQI48ePx9GjR3H48GGEhYVh1KhR0Gq1AIAxY8ZApVIhNDQUqamp2LJlC5YvX45p06aJ/Zg8eTL27NmDxYsX48yZM5gzZw6SkpIQFhZm0fMwJUFERLJwv5eGTkpKQv/+/cXPlV/iISEhmDNnDrZv3w4A6Natm0m9H3/8Ef369QMAREdHIywsDAMGDIBSqcTIkSMRGRkpltVoNNi3bx8mTpyIHj16oHnz5ggPDzdZq6FXr17YtGkT3nvvPbzzzjt4+OGHERMTgy5dulj0PAwYiIiIakG/fv1wr6WOqrMMkpubGzZt2nTPMo888ggOHjx4zzLPPfccnnvuObP3uxcGDEREJAvWmvQoVwwYiIhIFrhbpTQMGIiISBY4wiAN35IgIiIiszjCQEREsiBITEnIfYSBAQMREcmCAEDK/swNdmtnK2FKgoiIiMziCAMREcmCEQooLFyt8e/15YwBAxERyQLfkpCGKQkiIiIyiyMMREQkC0ZBAQUXbqoxBgxERCQLgiDxLQmZvybBlAQRERGZxREGIiKSBU56lIYBAxERyQIDBmkYMBARkSxw0qM0nMNAREREZnGEgYiIZIFvSUjDgIGIiGShImCQMofBip1pgJiSICIiIrM4wkBERLLAtySkYcBARESyIPxxSKkvZ0xJEBERkVkcYSAiIllgSkIaBgxERCQPzElIwoCBiIjkQeIIA2Q+wsA5DERERGQWRxiIiEgWuNKjNAwYiIhIFjjpURqmJIiIiMgsjjAQEZE8CAppExdlPsLAgIGIiGSBcxikYUqCiIiIzOIIAxERyQMXbpKEAQMREckC35KQploBw/bt26vd4NNPP13jzhAREVH9VK2AISgoqFqNKRQKGAwGKf0hIiKqPTJPK0hRrYDBaDTWdj+IiIhqFVMS0kh6S6K4uNha/SAiIqpdghUOGbM4YDAYDJg/fz4efPBBODk54fz58wCA2bNn4/PPP7d6B4mIiKjuWRwwfPjhh9iwYQMWLlwIlUolnu/SpQs+++wzq3aOiIjIehRWOOTL4oBh48aNWLNmDYKDg2FjYyOe9/X1xZkzZ6zaOSIiIqthSkISiwOGK1euoG3btlXOG41GlJWVWaVTREREVL9YHDB06tQJBw8erHL+m2++Qffu3a3SKSIiIqvjCIMkFq/0GB4ejpCQEFy5cgVGoxHfffcd0tPTsXHjRuzcubM2+khERCQdd6uUxOIRhuHDh2PHjh344Ycf4OjoiPDwcKSlpWHHjh146qmnaqOPREREVMdqtJdE7969ERsba+2+EBER1Rpuby1NjTefSkpKQlpaGoCKeQ09evSwWqeIiIisjrtVSmJxwHD58mWMHj0ahw8fhouLCwAgPz8fvXr1wubNm9GyZUtr95GIiIjqmMVzGF555RWUlZUhLS0NeXl5yMvLQ1paGoxGI1555ZXa6CMREZF0lZMepRwWiI+Px7Bhw6DVaqFQKBATE2PaHUFAeHg4WrRoAQcHBwQEBODcuXMmZfLy8hAcHAy1Wg0XFxeEhoaisLDQpMzJkyfRu3dv2Nvbw8vLCwsXLqzSl6+//hodOnSAvb09unbtit27d1v0LEANAoYDBw5g9erVaN++vXiuffv2WLFiBeLj4y3uABER0f2gEKQfligqKoKvry9WrVp1x+sLFy5EZGQkoqKikJiYCEdHRwQGBprs0xQcHIzU1FTExsZi586diI+Px4QJE8Trer0eAwcOhLe3N5KTk7Fo0SLMmTMHa9asEcscOXIEo0ePRmhoKE6cOIGgoCAEBQXh9OnTFj2PxSkJLy+vOy7QZDAYoNVqLW2OiIjo/rDSHAa9Xm9y2s7ODnZ2dlWKDx48GIMHD75zU4KAZcuW4b333sPw4cMBVKyk7OHhgZiYGIwaNQppaWnYs2cPjh07hp49ewIAVqxYgSFDhuCTTz6BVqtFdHQ0SktLsW7dOqhUKnTu3BkpKSlYsmSJGFgsX74cgwYNwowZMwAA8+fPR2xsLFauXImoqKhqP77FIwyLFi3CpEmTkJSUJJ5LSkrC5MmT8cknn1jaHBERUYPi5eUFjUYjHhERERa3kZmZCZ1Oh4CAAPGcRqOBn58fEhISAAAJCQlwcXERgwUACAgIgFKpRGJiolimT58+Jns7BQYGIj09HTdu3BDL/PU+lWUq71Nd1RphcHV1hULxZ+6mqKgIfn5+sLWtqF5eXg5bW1u8/PLLCAoKsqgDRERE94WVFm7KysqCWq0WT99pdMEcnU4HAPDw8DA57+HhIV7T6XRwd3c3uW5raws3NzeTMj4+PlXaqLzm6uoKnU53z/tUV7UChmXLllnUKBERUb1jpZSEWq02CRjkoloBQ0hISG33g4iISDY8PT0BADk5OWjRooV4PicnB926dRPL5ObmmtQrLy9HXl6eWN/T0xM5OTkmZSo/mytTeb26LJ7D8FfFxcXQ6/UmBxERUb1Ujzaf8vHxgaenJ+Li4sRzer0eiYmJ8Pf3BwD4+/sjPz8fycnJYpn9+/fDaDTCz89PLBMfH2/yMkJsbCzat28PV1dXscxf71NZpvI+1WVxwFBUVISwsDC4u7vD0dERrq6uJgcREVG9dJ8DhsLCQqSkpCAlJQVAxUTHlJQUXLp0CQqFAlOmTMEHH3yA7du349SpUxg7diy0Wq04F7Bjx44YNGgQxo8fj6NHj+Lw4cMICwvDqFGjxLcSx4wZA5VKhdDQUKSmpmLLli1Yvnw5pk2bJvZj8uTJ2LNnDxYvXowzZ85gzpw5SEpKQlhYmEXPY3HA8NZbb2H//v1YvXo17Ozs8Nlnn2Hu3LnQarXYuHGjpc0RERE1SklJSejevTu6d+8OAJg2bRq6d++O8PBwABXfp5MmTcKECRPw2GOPobCwEHv27IG9vb3YRnR0NDp06IABAwZgyJAhePLJJ03WWNBoNNi3bx8yMzPRo0cPTJ8+HeHh4SZrNfTq1QubNm3CmjVr4Ovri2+++QYxMTHo0qWLRc+jEATLttNo1aoVNm7ciH79+kGtVuP48eNo27YtvvzyS3z11Vc1Wj2qpvR6PTQaDW6cbQO1s6TsClG91X8cV1Clxqu8vBhHfpiDgoKCWptIWPld4bXoAygd7M1XuAvj7WJkzXivVvtan1n8LZuXl4c2bdoAqJgpmpeXBwB48sknudIjERHVW/d7pcfGxuKAoU2bNsjMzAQAdOjQAVu3bgUA7NixQ9yMioiIiBoXiwOGcePG4ZdffgEAzJo1C6tWrYK9vT2mTp0qLjtJRERU79SjtyQaIov3kpg6dar454CAAJw5cwbJyclo27YtHnnkEat2joiIiOoHiwOGv/P29oa3t7c1+kJERFRrFJA2D0HCotKNQrUChsjIyGo3+MYbb9S4M0RERFQ/VStgWLp0abUaUygUdRIwPNOuK2wVTe77fYnuh7KRNnXdBaJaU152H3++rbT5lFxVK2CofCuCiIiowbLS5lNyxdWOiIiIyCzJkx6JiIgaBI4wSMKAgYiIZEHqao1c6ZGIiIjIDI4wEBGRPDAlIUmNRhgOHjyIF154Af7+/rhy5QoA4Msvv8ShQ4es2jkiIiKr4dLQklgcMHz77bcIDAyEg4MDTpw4gZKSEgBAQUEBFixYYPUOEhERUd2zOGD44IMPEBUVhbVr16JJkz8XS3riiSdw/Phxq3aOiIjIWri9tTQWz2FIT09Hnz59qpzXaDTIz8+3Rp+IiIisjys9SmLxCIOnpycyMjKqnD906BDatGljlU4RERFZHecwSGJxwDB+/HhMnjwZiYmJUCgUuHr1KqKjo/Hmm2/itddeq40+EhERUR2zOCUxa9YsGI1GDBgwALdu3UKfPn1gZ2eHN998E5MmTaqNPhIREUnGhZuksThgUCgUePfddzFjxgxkZGSgsLAQnTp1gpOTU230j4iIyDq4DoMkNV64SaVSoVOnTtbsCxEREdVTFgcM/fv3h0Jx95mi+/fvl9QhIiKiWiH11UiOMFimW7duJp/LysqQkpKC06dPIyQkxFr9IiIisi6mJCSxOGBYunTpHc/PmTMHhYWFkjtERERE9Y/Vdqt84YUXsG7dOms1R0REZF1ch0ESq+1WmZCQAHt7e2s1R0REZFV8rVIaiwOGESNGmHwWBAHZ2dlISkrC7NmzrdYxIiIiqj8sDhg0Go3JZ6VSifbt22PevHkYOHCg1TpGRERE9YdFAYPBYMC4cePQtWtXuLq61lafiIiIrI9vSUhi0aRHGxsbDBw4kLtSEhFRg8PtraWx+C2JLl264Pz587XRFyIiIqqnLA4YPvjgA7z55pvYuXMnsrOzodfrTQ4iIqJ6i69U1li15zDMmzcP06dPx5AhQwAATz/9tMkS0YIgQKFQwGAwWL+XREREUnEOgyTVDhjmzp2LV199FT/++GNt9oeIiIjqoWoHDIJQEVr17du31jpDRERUW7hwkzQWvVZ5r10qiYiI6jWmJCSxKGBo166d2aAhLy9PUoeIiIio/rEoYJg7d26VlR6JiIgaAqYkpLEoYBg1ahTc3d1rqy9ERES1hykJSaq9DgPnLxAREcmXxW9JEBERNUgcYZCk2gGD0WiszX4QERHVKs5hkMbi7a2JiIgaJI4wSGLxXhJEREQkPxxhICIieeAIgyQMGIiISBY4h0EapiSIiIjILI4wEBGRPDAlIQlHGIiISBYqUxJSDksYDAbMnj0bPj4+cHBwwEMPPYT58+ebrGskCALCw8PRokULODg4ICAgAOfOnTNpJy8vD8HBwVCr1XBxcUFoaCgKCwtNypw8eRK9e/eGvb09vLy8sHDhwhr/Pd0NAwYiIqJa8PHHH2P16tVYuXIl0tLS8PHHH2PhwoVYsWKFWGbhwoWIjIxEVFQUEhMT4ejoiMDAQBQXF4tlgoODkZqaitjYWOzcuRPx8fGYMGGCeF2v12PgwIHw9vZGcnIyFi1ahDlz5mDNmjVWfR6mJIiISB6slJLQ6/Ump+3s7GBnZ1el+JEjRzB8+HAMHToUANC6dWt89dVXOHr0aEVzgoBly5bhvffew/DhwwEAGzduhIeHB2JiYjBq1CikpaVhz549OHbsGHr27AkAWLFiBYYMGYJPPvkEWq0W0dHRKC0txbp166BSqdC5c2ekpKRgyZIlJoGFVBxhICIieRCscADw8vKCRqMRj4iIiDverlevXoiLi8PZs2cBAL/88gsOHTqEwYMHAwAyMzOh0+kQEBAg1tFoNPDz80NCQgIAICEhAS4uLmKwAAABAQFQKpVITEwUy/Tp0wcqlUosExgYiPT0dNy4caPmf19/wxEGIiIiC2RlZUGtVouf7zS6AACzZs2CXq9Hhw4dYGNjA4PBgA8//BDBwcEAAJ1OBwDw8PAwqefh4SFe0+l0VXaJtrW1hZubm0kZHx+fKm1UXnN1da3po5re1yqtEBER1XOKPw4p9QFArVabBAx3s3XrVkRHR2PTpk1immDKlCnQarUICQmR0JO6wYCBiIjk4T6/VjljxgzMmjULo0aNAgB07doVFy9eREREBEJCQuDp6QkAyMnJQYsWLcR6OTk56NatGwDA09MTubm5Ju2Wl5cjLy9PrO/p6YmcnByTMpWfK8tYA+cwEBGRLNzv1ypv3boFpdL0a9bGxkbc/dnHxweenp6Ii4sTr+v1eiQmJsLf3x8A4O/vj/z8fCQnJ4tl9u/fD6PRCD8/P7FMfHw8ysrKxDKxsbFo37691dIRAAMGIiKiWjFs2DB8+OGH2LVrFy5cuIBt27ZhyZIleOaZZwAACoUCU6ZMwQcffIDt27fj1KlTGDt2LLRaLYKCggAAHTt2xKBBgzB+/HgcPXoUhw8fRlhYGEaNGgWtVgsAGDNmDFQqFUJDQ5GamootW7Zg+fLlmDZtmlWfhykJIiKSh/ucklixYgVmz56N119/Hbm5udBqtfi///s/hIeHi2XeeustFBUVYcKECcjPz8eTTz6JPXv2wN7eXiwTHR2NsLAwDBgwAEqlEiNHjkRkZKR4XaPRYN++fZg4cSJ69OiB5s2bIzw83KqvVAKAQvjrklMNjF6vh0ajQT8Mh62iSV13h6hWFI30q+suENWa8rJiHPvfbBQUFFRrImFNVH5XdP6/BbBR2ZuvcBeG0mKkfvpOrfa1PmNKgoiIiMxiSoKIiGSB21tLw4CBiIjkgbtVSsKUBBEREZnFEQYiIpIFpiSkYcBARETywJSEJExJEBERkVkcYSAiIllgSkIaBgxERCQPTElIwoCBiIjkgQGDJJzDQERERGZxhIGIiGSBcxikYcBARETywJSEJExJEBERkVkcYSAiIllQCAIUQs2HCaTUbQwYMBARkTwwJSEJUxJERERkFkcYiIhIFviWhDQMGIiISB6YkpCEKQkiIiIyiyMMREQkC0xJSMOAgYiI5IEpCUkYMBARkSxwhEEazmEgIiIiszjCQERE8sCUhCQMGIiISDbknlaQgikJIiIiMosjDEREJA+CUHFIqS9jDBiIiEgW+JaENExJEBERkVkcYSAiInngWxKSMGAgIiJZUBgrDin15YwpCSIiIjKLIwwy86+x1zF07O/w8CoFAFxMt0f0Ug8k/agGALzxcRa69y5EM48y3L6lRFqSIz7/sAWyMuxN2nnq+TyMmHANLduU4FahDeJ3arDqnZYAgJYPFeONjy6jVbsSODob8HtOE/y4zQX/XeIJQ7ni/j4wyVJzTRFeG56If3TKgn2Tcly+rsaC//ZDetYDAIB3XvgJQ/zOmtRJ/LUlpq8eYnLOv/MljBuUjIe0eSgtt8GJjBZ4Z22geN3DtRDT/30Qjz58FbdLmuD7xHb4dMfjMBj5u1i9xJSEJAwYZOZadhOsW9ACVzLtoFAATz2XhznrL2DiwHa4eNYe5042xf7vXHHtigrOruV4YXoOFnx1HiF+HWE0VnzZj5hwDSP/LxeffaDFmeNNYd/UKAYgAFBepsAP37gh45QDCgts0KbzbUxZdBlKJbD+oxZ19egkE84OJVg99X84fk6LN1cPRn6hPVo+oMfN23Ym5X7+1QsL/ttX/FxWbmNyva/vecwcfRCf7ngMx89qYWMjoE2LPPG6UmHEwle/R56+KV5dMhzNNbfw7gs/odyoxJodj9fuQ1KN8C0Jaeo0YIiPj8eiRYuQnJyM7OxsbNu2DUFBQXXZpUYvMVZj8nnDxy3wr7G/o0OPIlw8a4/vo5uJ13Iuq/DFx56IijsLD69SZF+0g5OmHCEzs/F+iA9SDjmLZTPTHMQ/6y7ZQXfpz/+cc6+osN+/EF38imrxyYgqBD+Vgtx8J0RE9xPPZf+urlKutFyJvJtN79iGjdKIySMTsCrGD7t+7iCev6BzFf/8eMfLaO2Zjykrh+LGzabIuAJ8tqsnXhueiHW7e6DcYHOnpqkucR0GSeo0YCgqKoKvry9efvlljBgxoi67IktKpYDew/Jh19SItCTHKtftHAwY+O88ZF9U4drVJgCAR/sUQqkAmnuWYe2BM3BwNCItqSnWzNPi2lXVHe+jbV2Cnv1v4vBuzR2vE1nTE10u4uiZlpj/ciy6tc3GtXxHbDvUCTuOdDQp171tNnYs2Iibt+yQfFaLtTsfg/5WReqtndd1uLsWQRAUWPfWt3BT30LGleZYFeOHzGw3AEDn1rk4f9UNN/4SdBw90xIzRh2CT4sbOHe5+f17aKL7oE4DhsGDB2Pw4MHVLl9SUoKSkhLxs16vr41uNXqtO9zGsh0ZUNkZcbtIiXmhrXHp3J9zFP4Vch2vvJcNB0cjsjLs8PaoNigvq8jJenqXQKEERr2Ri9WztSi6aYOXZuoQsfk8Xh3QTiwHAEu3n0PbLrehshew60s3bFzked+fleRH2/wmgp5Mw5Yfu2Ljvu7o2Ooapow8grJyG+w52g5AxXyFAymtkf27Gg8+oMeEfx3FJ69/j1cXD4dRUELbrOL/lpeHJGPFd/+ALs8Zo/55Eive2IHR8/+Nm7fs0Ux9C3k3HUzunaevCB6aqW/h3P19bKoGpiSkaVAzcyIiIqDRaMTDy8urrrvUIF3+zQ6vP9UObwx9GDs3Nsebyy+h1cPF4vX937ni9YHtMP2Zh3D5vB3e/fQimthVvE+kVABNVAL+M/tBJB9Q48xxR0S85g2tTwl8exWa3GfBq96YGNgOEa+3wuMDbuLZ167d1+ckeVIqBJzNao41Ox7HucvNsf1IR2w/0gFBT/4qlok73haHT7fG+Ww3HDzZGjM/HYRO3tfQ/eHsP9qoKLdxb3cc+KUN0rMewILofhAEBf7Z/XxdPBZZg2CFQ8YaVMDw9ttvo6CgQDyysrLquksNUnmZElcv2CHjVFOsj2iBzF8dEPTKn1/mt27a4GqmHU4nOuGD8d7waluCJwYXAADycitSE5fO/jlHoSDPFvo8W7g/WGZyn2tXVbh0zh4/xbhi3YIWeGG6DkqlzP/FUa37Xd8UF3QuJucu5rjCw7XwzhUAXP1djRs37dHygYqf8+t/jBT8dc5CWbkNsn93Ftv5Xd8Ubs63TdpxU98SrxE1Ng0qYLCzs4NarTY5SDrFH6MGd7sGhSBeTz1WMdeh5UN/poacXcqhditHzpU7z2EAKuZL2NoKUDSonzhqiE6d90ArjwKTc17u+dDlOd+lBvCASyE0jsW4XlDxRZ+e1RwlZTbwcs8Xy9gojfB0KxTbSb3gjjbaPLg4/Rk0PNb+CgpvNzEJNKj+qExJSDnkjK9Vysy4t7NxbL8zrl1RwcHJgP7P5OORXoV4d0wbeLYqQd+n85F8wBkFebZ4oEUZng/LReltJY7GVfwneeW8HY7sUeO1eVex/K2WKLqpxMvv6HA5ww6/HHYCAPR/5gYM5QpkptmjrFSBdr63Me7tbBzY7sJ1GKjWbfmxK6Km/Q8vDjyB/cfboJP3NTzd6wwWbu4NAHBQlWHc4GQc+MUHv+ub4sHmerw+PBFXrmtw9ExFmvNWsQr/O9QRoUOSkZvvBF2eE8YM+AUA8OOJNgCAo2ktcUHngtljf8Tq//nBzfkWxv/rGL472LnKK5pUT/AtCUkYMMiMS/NyzIi8BDf3cty6aYPMNHu8O6YNjsc7w82jDF38ivDM+Otw0hiQf90Wp352xNThbVHwexOxjUVvtML/zb2KeRszIRiBkz874d3gNmIwYDQAz0/MxYNtSqBQALmXm2D7+ub4bu0DdfXYJCNnLrnjnbUD8X9PH8VLg44j+3dnRH7nj9ikhwEABkGBhx7Mw2C/s3ByKMX1gqY4dqYl1u7qafJFvyrmHzAYlZj94o+wa1KOXy+6Y/KKoeJ6DkZBibeiBuHNfx9C1LQY3C5pgj1H2+HzXT3r5LmJaptCEOouZCosLERGRgYAoHv37liyZAn69+8PNzc3tGrVymx9vV4PjUaDfhgOW0UTs+WJGqKikX513QWiWlNeVoxj/5uNgoKCWkszV35X+A+eB9sm9uYr3EV5WTESvg+v1b7WZ3U6wpCUlIT+/fuLn6dNmwYACAkJwYYNG+qoV0RE1ChxaWhJ6jRg6NevH+pwgIOIiIiqiXMYiIhIFrhwkzQMGIiISB6MQsUhpb6M8a14IiKShzpY6fHKlSt44YUX0KxZMzg4OKBr165ISkr6s0uCgPDwcLRo0QIODg4ICAjAuXOmC4vn5eUhODgYarUaLi4uCA0NRWGh6UJkJ0+eRO/evWFvbw8vLy8sXLjQ8s6awYCBiIioFty4cQNPPPEEmjRpgu+//x6//vorFi9eDFfXPxf2WrhwISIjIxEVFYXExEQ4OjoiMDAQxcV/LtcfHByM1NRUxMbGYufOnYiPj8eECRPE63q9HgMHDoS3tzeSk5OxaNEizJkzB2vWrLHq8zAlQUREsvDHwrWS6lvi448/hpeXF9avXy+e8/HxEf8sCAKWLVuG9957D8OHDwcAbNy4ER4eHoiJicGoUaOQlpaGPXv24NixY+jZs2KNjxUrVmDIkCH45JNPoNVqER0djdLSUqxbtw4qlQqdO3dGSkoKlixZYhJYSMURBiIikofKlR6lHKj4jf6vx193Uf6r7du3o2fPnnjuuefg7u6O7t27Y+3ateL1zMxM6HQ6BAQEiOc0Gg38/PyQkJAAAEhISICLi4sYLABAQEAAlEolEhMTxTJ9+vSBSvXn8vyBgYFIT0/HjRs3rPbXx4CBiIjIAl5eXiY7J0dERNyx3Pnz57F69Wo8/PDD2Lt3L1577TW88cYb+OKLLwAAOp0OAODh4WFSz8PDQ7ym0+ng7u5uct3W1hZubm4mZe7Uxl/vYQ1MSRARkSxY67XKrKwsk5Ue7ezs7ljeaDSiZ8+eWLBgAYCKFY1Pnz6NqKgohISE1LwjdYQjDEREJA9Wekvi77sm3y1gaNGiBTp16mRyrmPHjrh06RIAwNPTEwCQk5NjUiYnJ0e85unpidzcXJPr5eXlyMvLMylzpzb+eg9rYMBARERUC5544gmkp6ebnDt79iy8vb0BVEyA9PT0RFxcnHhdr9cjMTER/v7+AAB/f3/k5+cjOTlZLLN//34YjUb4+fmJZeLj41FWViaWiY2NRfv27U3eyJCKAQMREcmCQhAkH5aYOnUqfv75ZyxYsAAZGRnYtGkT1qxZg4kTJ1b0R6HAlClT8MEHH2D79u04deoUxo4dC61Wi6CgIAAVIxKDBg3C+PHjcfToURw+fBhhYWEYNWoUtFotAGDMmDFQqVQIDQ1FamoqtmzZguXLl4v7M1kL5zAQEZE8GP84pNS3wGOPPYZt27bh7bffxrx58+Dj44Nly5YhODhYLPPWW2+hqKgIEyZMQH5+Pp588kns2bMH9vZ/7qoZHR2NsLAwDBgwAEqlEiNHjkRkZKR4XaPRYN++fZg4cSJ69OiB5s2bIzw83KqvVAJ1vL21VNzemuSA21tTY3Y/t7fu3ed92NpK2N66vBgH4+dye2siIqLGrCZphb/XlzMGDEREJA813A/CpL6MMWAgIiJ5+MtqjTWuL2N8S4KIiIjM4ggDERHJgrVWepQrBgxERCQPTElIwpQEERERmcURBiIikgWFseKQUl/OGDAQEZE8MCUhCVMSREREZBZHGIiISB64cJMkDBiIiEgWuDS0NExJEBERkVkcYSAiInngpEdJGDAQEZE8CACkvBop73iBAQMREckD5zBIwzkMREREZBZHGIiISB4ESJzDYLWeNEgMGIiISB446VESpiSIiIjILI4wEBGRPBgBKCTWlzEGDEREJAt8S0IapiSIiIjILI4wEBGRPHDSoyQMGIiISB4YMEjClAQRERGZxREGIiKSB44wSMKAgYiI5IGvVUrCgIGIiGSBr1VKwzkMREREZBZHGIiISB44h0ESBgxERCQPRgFQSPjSN8o7YGBKgoiIiMziCAMREckDUxKSMGAgIiKZkBgwQN4BA1MSREREZBZHGIiISB6YkpCEAQMREcmDUYCktALfkiAiIiK6N44wEBGRPAjGikNKfRljwEBERPLAOQySMGAgIiJ54BwGSTiHgYiIiMziCAMREckDUxKSMGAgIiJ5ECAxYLBaTxokpiSIiIjILI4wEBGRPDAlIQkDBiIikgejEYCEtRSM8l6HgSkJIiIiMosBAxERyUNlSkLKUUMfffQRFAoFpkyZIp4rLi7GxIkT0axZMzg5OWHkyJHIyckxqXfp0iUMHToUTZs2hbu7O2bMmIHy8nKTMj/99BMeffRR2NnZoW3bttiwYUON+3kvDBiIiEge6ihgOHbsGD799FM88sgjJuenTp2KHTt24Ouvv8aBAwdw9epVjBgxQrxuMBgwdOhQlJaW4siRI/jiiy+wYcMGhIeHi2UyMzMxdOhQ9O/fHykpKZgyZQpeeeUV7N27t2Z/R/fAgIGIiKiWFBYWIjg4GGvXroWrq6t4vqCgAJ9//jmWLFmCf/7zn+jRowfWr1+PI0eO4OeffwYA7Nu3D7/++iv++9//olu3bhg8eDDmz5+PVatWobS0FAAQFRUFHx8fLF68GB07dkRYWBieffZZLF261OrPwoCBiIjkwShIPwDo9XqTo6Sk5K63nDhxIoYOHYqAgACT88nJySgrKzM536FDB7Rq1QoJCQkAgISEBHTt2hUeHh5imcDAQOj1eqSmpopl/t52YGCg2IY1MWAgIiJZEASj5AMAvLy8oNFoxCMiIuKO99u8eTOOHz9+x+s6nQ4qlQouLi4m5z08PKDT6cQyfw0WKq9XXrtXGb1ej9u3b1v+l3QPfK2SiIjkQRCkbSD1xxyGrKwsqNVq8bSdnV2VollZWZg8eTJiY2Nhb29f83vWIxxhICIisoBarTY57hQwJCcnIzc3F48++ihsbW1ha2uLAwcOIDIyEra2tvDw8EBpaSny8/NN6uXk5MDT0xMA4OnpWeWticrP5sqo1Wo4ODhY65EBMGAgIiK5uI9vSQwYMACnTp1CSkqKePTs2RPBwcHin5s0aYK4uDixTnp6Oi5dugR/f38AgL+/P06dOoXc3FyxTGxsLNRqNTp16iSW+WsblWUq27AmpiSIiEgejEZAIWG1RqH6dZ2dndGlSxeTc46OjmjWrJl4PjQ0FNOmTYObmxvUajUmTZoEf39//OMf/wAADBw4EJ06dcKLL76IhQsXQqfT4b333sPEiRPFUY1XX30VK1euxFtvvYWXX34Z+/fvx9atW7Fr166aP+ddMGAgIiKqA0uXLoVSqcTIkSNRUlKCwMBA/Oc//xGv29jYYOfOnXjttdfg7+8PR0dHhISEYN68eWIZHx8f7Nq1C1OnTsXy5cvRsmVLfPbZZwgMDLR6fxWC0HB309Dr9dBoNOiH4bBVNKnr7hDViqKRfnXdBaJaU15WjGP/m42CggKTiYTWVPldMcBpDGwVqhq3Uy6UIq5wU632tT7jCAMREcmCYDRCkJCSECxISTRGnPRIREREZnGEgYiI5EEQAEhfh0GuGDAQEZE8GAVAwYChppiSICIiIrM4wkBERPIgCACkrMMg7xEGBgxERCQLglGAICEl0YBXIbAKBgxERCQPghHSRhj4WiURERHRPXGEgYiIZIEpCWkYMBARkTwwJSFJgw4YKqO9cpRJWouDqD4rLyuu6y4Q1RrDHz/f9+O3d6nfFeUos15nGqAGvfnU5cuX4eXlVdfdICIiibKystCyZctaabu4uBg+Pj7Q6XSS2/L09ERmZibs7e2t0LOGpUEHDEajEVevXoWzszMUCkVdd0cW9Ho9vLy8kJWVJcvd2qhx48/3/ScIAm7evAmtVgulsvbm4RcXF6O0tFRyOyqVSpbBAtDAUxJKpbLWIlK6N7Vazf9QqdHiz/f9pdFoav0e9vb2sv2itxa+VklERERmMWAgIiIisxgwkEXs7Ozw/vvvw87Orq67QmR1/PkmursGPemRiIiI7g+OMBAREZFZDBiIiIjILAYMREREZBYDBiIiIjKLAQNV26pVq9C6dWvY29vDz88PR48eresuEVlFfHw8hg0bBq1WC4VCgZiYmLruElG9w4CBqmXLli2YNm0a3n//fRw/fhy+vr4IDAxEbm5uXXeNSLKioiL4+vpi1apVdd0VonqLr1VStfj5+eGxxx7DypUrAVTs4+Hl5YVJkyZh1qxZddw7IutRKBTYtm0bgoKC6rorRPUKRxjIrNLSUiQnJyMgIEA8p1QqERAQgISEhDrsGRER3S8MGMis69evw2AwwMPDw+S8h4eHVbaLJSKi+o8BAxEREZnFgIHMat68OWxsbJCTk2NyPicnB56ennXUKyIiup8YMJBZKpUKPXr0QFxcnHjOaDQiLi4O/v7+ddgzIiK6X2zrugPUMEybNg0hISHo2bMnHn/8cSxbtgxFRUUYN25cXXeNSLLCwkJkZGSInzMzM5GSkgI3Nze0atWqDntGVH/wtUqqtpUrV2LRokXQ6XTo1q0bIiMj4efnV9fdIpLsp59+Qv/+/aucDwkJwYYNG+5/h4jqIQYMREREZBbnMBAREZFZDBiIiIjILAYMREREZBYDBiIiIjKLAQMRERGZxYCBiIiIzGLAQERERGYxYCAiIiKzGDAQSfTSSy8hKChI/NyvXz9MmTLlvvfjp59+gkKhQH5+/l3LKBQKxMTEVLvNOXPmoFu3bpL6deHCBSgUCqSkpEhqh4jqFgMGapReeuklKBQKKBQKqFQqtG3bFvPmzUN5eXmt3/u7777D/Pnzq1W2Ol/yRET1ATefokZr0KBBWL9+PUpKSrB7925MnDgRTZo0wdtvv12lbGlpKVQqlVXu6+bmZpV2iIjqE44wUKNlZ2cHT09PeHt747XXXkNAQAC2b98O4M80wocffgitVov27dsDALKysvD888/DxcUFbm5uGD58OC5cuCC2aTAYMG3aNLi4uKBZs2Z466238PftWP6ekigpKcHMmTPh5eUFOzs7tG3bFp9//jkuXLggbnjk6uoKhUKBl156CUDF9uERERHw8fGBg4MDfH198c0335jcZ/fu3WjXrh0cHBzQv39/k35W18yZM9GuXTs0bdoUbdq0wezZs1FWVlal3KeffgovLy80bdoUzz//PAoKCkyuf/bZZ+jYsSPs7e3RoUMH/Oc//7G4L0RUvzFgINlwcHBAaWmp+DkuLg7p6emIjY3Fzp07UVZWhsDAQDg7O+PgwYM4fPgwnJycMGjQILHe4sWLsWHDBqxbtw6HDh1CXl4etm3bds/7jh07Fl999RUiIyORlpaGTz/9FE5OTvDy8sK3334LAEhPT0d2djaWL18OAIiIiMDGjRsRFRWF1NRUTJ06FS+88AIOHDgAoCKwGTFiBIYNG4aUlBS88sormDVrlsV/J87OztiwYQN+/fVXLF++HGvXrsXSpUtNymRkZGDr1q3YsWMH9uzZgxMnTuD1118Xr0dHRyM8PBwffvgh0tLSsGDBAsyePRtffPGFxf0honpMIGqEQkJChOHDhwuCIAhGo1GIjY0V7OzshDfffFO87uHhIZSUlIh1vvzyS6F9+/aC0WgUz5WUlAgODg7C3r17BUEQhBYtWggLFy4Ur5eVlQktW7YU7yUIgtC3b19h8uTJgiAIQnp6ugBAiI2NvWM/f/zxRwGAcOPGDfFccXGx0LRpU+HIkSMmZUNDQ4XRo0cLgiAIb7/9ttCpUyeT6zNnzqzS1t8BELZt23bX64sWLRJ69Oghfn7//fcFGxsb4fLly+K577//XlAqlUJ2drYgCILw0EMPCZs2bTJpZ/78+YK/v78gCIKQmZkpABBOnDhx1/sSUf3HOQzUaO3cuRNOTk4oKyuD0WjEmDFjMGfOHPF6165dTeYt/PLLL8jIyICzs7NJO8XFxfjtt99QUFCA7Oxs+Pn5iddsbW3Rs2fPKmmJSikpKbCxsUHfvn2r3e+MjAzcunULTz31lMn50tJSdO/eHQCQlpZm0g8A8Pf3r/Y9Km3ZsgWRkZH47bffUFhYiPLycqjVapMyrVq1woMPPmhyH6PRiPT0dDg7O+O3335DaGgoxo8fL5YpLy+HRqOxuD9EVH8xYKBGq3///li9ejVUKhW0Wi1sbU1/3B0dHU0+FxYWokePHoiOjq7S1gMPPFCjPjg4OFhcp7CwEACwa9cuky9qoGJehrUkJCQgODgYc+fORWBgIDQaDTZv3ozFixdb3Ne1a9dWCWBsbGys1lciqnsMGKjRcnR0RNu2batd/tFHH8WWLVvg7u5e5bfsSi1atEBiYiL69OkDoOI36eTkZDz66KN3LN+1a1cYjUYcOHAAAQEBVa5XjnAYDAbxXKdOnWBnZ4dLly7ddWSiY8eO4gTOSj///LP5h/yLI0eOwNvbG++++6547uLFi1XKXbp0CVevXoVWqxXvo1Qq0b59e3h4eECr1eL8+fMIDg626P5E1LBw0iPRH4KDg9G8eXMMHz4cBw8eRGZmJn766Se88cYbuHz5MgBg8uTJ+OijjxATE4MzZ87g9ddfv+caCq1bt0ZISAhefvllxMTEiG1u3boVAODt7Q2FQoGdO3fi2rVrKCwshLOzM958801MnToVX3zxBX777TccP34cK1asECcSvvrqqzh37hxmzJiB9PR0bNq0CRs2bLDoeR9++GFcunQJmzdvxm+//YbIyMg7TuC0t7dHSEgIfvnlFxw8eBBvvPEGnn/+eXh6egIA5s6di4iICERGRuLs2bM4deoU1q9fjyVLlljUHyKq3xgwEP2hadOmiI+PR6tWrTBixAh07NgRoaGhKC4uFkccpk+fjhdffBEhISHw9/eHs7MznnnmmXu2u3r1ajz77LN4/fXX0aFDB4wfPx5FRUUAgAcffBBz587FrFmz4OHhgbCwMADA/PnzMXv2bERERKBjx44YNGgQdu3aBR8fHwAV8wq+/fZbxMTEwNfXF1FRUViwYIFFz/v0009j6tSpCAsLQ7du3XDkyBHMnj27Srm2bdtixIgRGDJkCAYOHIhHHnnE5LXJV155BZ999hnWr1+Prl27om/fvtiwYYPYVyJqHBTC3WZrEREREf2BIwxERERkFgMGIiIiMosBAxEREZnFgIGIiIjMYsBAREREZjFgICIiIrMYMBAREZFZDBiIiIjILAYMREREZBYDBiIiIjKLAQMRERGZ9f9OOAo7qVyPFgAAAABJRU5ErkJggg=="/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="c1">## Ok so the thing here is</span>
<span class="c1">### predicting 1 when it's 0 costs us $100</span>
<span class="c1">### predicting 0 when it's 1 costs us $40</span>
<span class="c1">### If I make a mistake, I want to be doing false negatives (predict 0 but not 0) instead of false positives (predict 1 but not 1)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">cm</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span> <span class="o">*</span> <span class="mi">100</span> <span class="o">+</span> <span class="n">cm</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span> <span class="o">*</span> <span class="mi">40</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>736820</pre>
</div>
</div>
</div>
</div>
</div>
<!-- At the last cell of the 1st model where I speak of what this means for the business -->
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">So with a LogisticRegression model, we're getting 70% accuracy and losing around 736K dollars because of it<a class="anchor-link" href="#So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">¶</a></h3>
</div>
</div>
</div>
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Try-to-re-run-the-LogisticRegression-model-but-adjust-the-weights">Try to re-run the LogisticRegression model but adjust the weights<a class="anchor-link" href="#Try-to-re-run-the-LogisticRegression-model-but-adjust-the-weights">¶</a></h2>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.utils</span> <span class="kn">import</span> <span class="n">class_weight</span>
<span class="n">log_model_weighted</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">(</span><span class="n">class_weight</span><span class="o">=</span><span class="nb">dict</span><span class="p">(</span><span class="nb">enumerate</span><span class="p">(</span><span class="n">class_weight</span><span class="o">.</span><span class="n">compute_class_weight</span><span class="p">({</span><span class="mi">0</span><span class="p">:</span> <span class="mf">.8</span><span class="p">,</span> <span class="mi">1</span><span class="p">:</span> <span class="mf">1.5</span><span class="p">},</span><span class="n">classes</span><span class="o">=</span><span class="n">np</span><span class="o">.</span><span class="n">unique</span><span class="p">(</span><span class="n">y_train</span><span class="p">),</span> <span class="n">y</span><span class="o">=</span><span class="n">y_train</span><span class="p">))))</span>
<span class="n">log_model_fit_weighted</span> <span class="o">=</span> <span class="n">log_model_weighted</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">preds_log_weighted</span> <span class="o">=</span> <span class="n">log_model_weighted</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">accuracy_score</span><span class="p">(</span><span class="n">preds_log_weighted</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>0.696139398339594</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span><span class="p">,</span> <span class="n">ConfusionMatrixDisplay</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">preds_log_weighted</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
<span class="n">disp</span> <span class="o">=</span> <span class="n">ConfusionMatrixDisplay</span><span class="p">(</span><span class="n">confusion_matrix</span><span class="o">=</span><span class="n">cm</span><span class="p">)</span>
<span class="n">disp</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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osIAALAGJj2aQsIAALAGEgZTaEkAAFDDnn76adlsNo0YMcK1r7i4WEOHDlXTpk3VuHFj3XTTTcrJyXE7b+/evbruuuvUqFEjNW/eXA8//LDKy8vdxnz99de6+OKLFRAQoDZt2mjOnDk18hlIGAAA1nC8wmBmOw1r1qzR7NmzdeGFF7rtHzlypD755BO9//77+uabb3Tw4EH179/fddzhcOi6665TaWmpVqxYobfeektz5szR+PHjXWOysrJ03XXXqWfPnsrIyNCIESN0zz336PPPPz+9n9EpkDAAAKzB6YWtmgoLC5WcnKxXX31VTZo0ce3Pz8/X66+/runTp+uvf/2runbtqjfffFMrVqzQDz/8IEn64osv9NNPP+nf//63unTpoj59+mjSpEmaOXOmSktLJUmzZs1SXFycnnvuOXXo0EHDhg3TzTffrOeff/60fkSnQsIAALCE48sqzWySVFBQ4LaVlJSc9D2HDh2q6667TomJiW7709PTVVZW5ra/ffv2atWqlVauXClJWrlypTp16qTIyEjXmKSkJBUUFGjz5s2uMX++dlJSkusa3kTCAABANcTExCgsLMy1TZky5YTj3nvvPa1bt+6Ex7Ozs+Xv76/w8HC3/ZGRkcrOznaN+WOycPz48WOnGlNQUKBff/31tD7fybBKAgBgDV5aJbFv3z6Fhoa6dgcEBFQaum/fPg0fPlxpaWkKDAw8/fesQ6gwAACswWmY3ySFhoa6bSdKGNLT03X48GFdfPHF8vX1la+vr7755hulpqbK19dXkZGRKi0tVV5entt5OTk5ioqKkiRFRUVVWjVx/LWnMaGhoQoKCvLKj+04EgYAALzs6quv1saNG5WRkeHaunXrpuTkZNd/+/n5aenSpa5zMjMztXfvXiUkJEiSEhIStHHjRh0+fNg1Ji0tTaGhoerYsaNrzB+vcXzM8Wt4Ey0JAIA1nMEbN4WEhOiCCy5w2xccHKymTZu69g8aNEijRo1SRESEQkND9cADDyghIUF/+ctfJEm9evVSx44ddccdd2jq1KnKzs7W2LFjNXToUFdV47777tNLL72kRx55RHfffbeWLVumBQsW6NNPPz39z3kSJAwAAIswmTDIu3d6fP7552W323XTTTeppKRESUlJ+te//uU67uPjo8WLF2vIkCFKSEhQcHCwUlJS9MQTT7jGxMXF6dNP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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">cm</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span> <span class="o">*</span> <span class="mi">100</span> <span class="o">+</span> <span class="n">cm</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span> <span class="o">*</span> <span class="mi">40</span> <span class="c1"># Managed to get that down to 560-600K just by updating the weights and making 0:1 ratio be 1.8~2.5</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>559100</pre>
</div>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added business comment to the ends of the 2nd Logistic Regression Model -->
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">So with this other LogisticRegression model, we're getting a 69.6% accuracy and losing around 559K dollars because of it. Slight improvement but might be able to do better<a class="anchor-link" href="#So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">¶</a></h3>
</div>
</div>
</div>
</div>
<!-- End of newly added business comment to the ends of the 2nd Logistic Regression Model -->

<!-- I'm at 'Let's try running a neural network model for this' -->

<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Let's-try-running-a-neural-network-model-for-this">Let's try running a neural network model for this<a class="anchor-link" href="#Let's-try-running-a-neural-network-model-for-this">¶</a></h2>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Sequential</span><span class="p">()</span>
<span class="n">model</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Input</span><span class="p">(</span><span class="n">shape</span> <span class="o">=</span> <span class="p">(</span><span class="mi">67</span><span class="p">,)))</span>
<span class="n">model</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">50</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'linear'</span><span class="p">))</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model</span><span class="o">.</span><span class="n">compile</span><span class="p">(</span><span class="n">optimizer</span> <span class="o">=</span> <span class="s1">'adam'</span><span class="p">,</span>
              <span class="n">loss</span> <span class="o">=</span> <span class="s1">'mean_squared_error'</span><span class="p">,</span>
              <span class="n">metrics</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'MeanSquaredError'</span><span class="p">])</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of the deleted scaled_x.shape cell, input and output -->

<!-- End of the deleted scaled_x.shape cell, input and output -->
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">epochs</span> <span class="o">=</span> <span class="mi">80</span><span class="p">,</span> <span class="n">validation_data</span><span class="o">=</span> <span class="p">(</span><span class="n">X_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">),</span><span class="n">batch_size</span> <span class="o">=</span> <span class="mi">50</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of the deleted output of the first NN model -->

<!-- End of the deleted output of the first NN model -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">preds</span> <span class="o">=</span> <span class="n">model</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of the deleted output for preds = model.predict(X_test) -->

<!-- End of the deleted output for preds = model.predict(X_test) -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">make_class</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">preds</span><span class="p">:</span>
  <span class="k">if</span> <span class="n">i</span> <span class="o">&gt;</span> <span class="mf">.5</span><span class="p">:</span>
    <span class="n">make_class</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
  <span class="k">else</span><span class="p">:</span>
    <span class="n">make_class</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span><span class="p">,</span> <span class="n">ConfusionMatrixDisplay</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">make_class</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
<span class="n">disp</span> <span class="o">=</span> <span class="n">ConfusionMatrixDisplay</span><span class="p">(</span><span class="n">confusion_matrix</span><span class="o">=</span><span class="n">cm</span><span class="p">)</span>
<span class="n">disp</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
<span class="c1"># So predicted 515 0s that aren't 0; Each cost us $25</span>
<span class="c1"># So predicted 533 1s that aren't 1; Each cost us $100</span>

<span class="c1">## 31679 row, had 1048 wrongfully predicted</span>
<span class="mi">1048</span><span class="o">/</span><span class="mi">31679</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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"/>
</div>
</div>
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>0.03308185233119732</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">cm</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span> <span class="o">*</span> <span class="mi">100</span> <span class="o">+</span> <span class="n">cm</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span> <span class="o">*</span> <span class="mi">40</span> <span class="c1"># Down to 92k, with a Deep Learning Neural Network</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>92600</pre>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added business comment to the ends of the 1st NN model -->
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">
So with the 1st NN model, we're getting a 96.6% accuracy and losing around 92,600 dollars because of it. Huge improvement but tweaking hyperparameters more. <a class="anchor-link" href="#So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">¶</a></h3>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added business comment to the ends of the 1st NN model -->
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Alter-the-settings-to-see-how-it-runs-then">Alter the settings to see how it runs then<a class="anchor-link" href="#Alter-the-settings-to-see-how-it-runs-then">¶</a></h2>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model2</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Sequential</span><span class="p">()</span>
<span class="n">model2</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Input</span><span class="p">(</span><span class="n">shape</span> <span class="o">=</span> <span class="p">(</span><span class="mi">67</span><span class="p">,)))</span>
<span class="n">model2</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'tanh'</span><span class="p">))</span>
<span class="n">model2</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">50</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model2</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model2</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'sigmoid'</span><span class="p">))</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model2</span><span class="o">.</span><span class="n">compile</span><span class="p">(</span><span class="n">optimizer</span> <span class="o">=</span> <span class="s1">'adam'</span><span class="p">,</span>
              <span class="n">loss</span> <span class="o">=</span> <span class="s1">'binary_crossentropy'</span><span class="p">,</span>
              <span class="n">metrics</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'FalsePositives'</span><span class="p">])</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model2</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">epochs</span> <span class="o">=</span> <span class="mi">80</span><span class="p">,</span><span class="n">batch_size</span> <span class="o">=</span> <span class="mi">50</span><span class="p">,</span> <span class="n">validation_data</span><span class="o">=</span> <span class="p">(</span><span class="n">X_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">))</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of deleted output of model2.fit(X_train, y_train, epochs = 80,batch_size = 50, validation_data= (X_test, y_test))-->

<!-- End of deleted output of model2.fit(X_train, y_train, epochs = 80,batch_size = 50, validation_data= (X_test, y_test))-->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">preds2</span> <span class="o">=</span> <span class="n">model2</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of deleted output ofpreds2 = model2.predict(X_test) -->

<!-- End of deleted output ofpreds2 = model2.predict(X_test) -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell jp-mod-noOutputs">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">make_class2</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">preds2</span><span class="p">:</span>
  <span class="k">if</span> <span class="n">i</span> <span class="o">&gt;</span> <span class="mf">.5</span><span class="p">:</span>
    <span class="n">make_class2</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
  <span class="k">else</span><span class="p">:</span>
    <span class="n">make_class2</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span><span class="p">,</span> <span class="n">ConfusionMatrixDisplay</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">make_class2</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
<span class="n">disp</span> <span class="o">=</span> <span class="n">ConfusionMatrixDisplay</span><span class="p">(</span><span class="n">confusion_matrix</span><span class="o">=</span><span class="n">cm</span><span class="p">)</span>
<span class="n">disp</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
<span class="c1">#</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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mopx48bBy8sLERERVr0fJgxERCQPDTyGoX379iav33nnHdxzzz0mKyY7OjrC09Pztufv2bMHP//8M/bu3QsPDw/06tULCQkJiI2NRXx8PJRKJdauXQtfX18sXboUANC9e3ccOnQIy5cvt3rCwC4JIiKSheoxDFI2ADWe0lxeXm72vfV6PT777DO8+OKLJrMOk5KS0K5dO/To0QOzZ8/GjRs3xGMZGRkIDAyEh4eHuC8iIgI6nQ6nTp0S24SFhZm8V0REBDIyMqR8q26LFQYiIiILeHt7m7yeN28e4uPj73pOcnIyrl27hueff17cN2rUKPj4+ECj0eD48eOIjY1FdnY2vvrqKwCAVqs1SRYAiK+1Wu1d2+h0Oty8eRMODg51ucXbYsJARETyYKUuiYsXL0KtVou7VSqV2VM3bNiAwYMHQ6PRiPsmTJggfh0YGAgvLy889thjOHv2LO655x4JgdYPdkkQEZEsWKtLQq1Wm2zmEoYLFy5g7969GDdu3F3bhYSEAABycnIAAJ6enigoKDBpU/26etzDndqo1WqrVhcAJgxERET16uOPP4a7uzuGDh1613ZZWVkAAC8vLwBAaGgoTpw4gatXr4ptUlJSoFarERAQILZJTU01uU5KSgpCQ0OteAdVmDAQEZE8NPA6DEDVoocff/wxoqKiYGd3axTA2bNnkZCQgMzMTJw/fx7ffPMNxo4di379+qFnz54AgPDwcAQEBOC5557DTz/9hG+//RZz5szBpEmTxKrGxIkTce7cObz22ms4c+YMPvjgA2zduhXTp0+v07fobpgwEBGRPDRCwrB3717k5eXhxRdfNNmvVCqxd+9ehIeHw9/fHzNmzMAzzzyD7du3i21sbW2xY8cO2NraIjQ0FGPGjMHYsWNN1m3w9fXFzp07kZKSgqCgICxduhTr16+3+pRKgIMeiYiI6k14ePhtn8Xk7e2NAwcOmD3fx8cHu3btumubAQMG4NixY3WOsbaYMBARkSwo/tyknC9nTBiIiEge+LRKSZgwEBGRLPBpldJw0CMRERGZxQoDERHJA7skJGHCQERE8iHzD30p2CVBREREZrHCQEREssBBj9IwYSAiInngGAZJ2CVBREREZrHCQEREssAuCWmYMBARkTywS0ISdkkQERGRWawwEBGRLLBLQhomDEREJA/skpCECQMREckDEwZJOIaB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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">cm</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span> <span class="o">*</span> <span class="mi">100</span> <span class="o">+</span> <span class="n">cm</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span> <span class="o">*</span> <span class="mi">40</span> <span class="c1"># Down to 65k, with a Deep Learning Neural Network. Add more nodes to the tanh layer to see what happens</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>65460</pre>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<!-- Beginning of deleted X_test.shape cell, input and output -->

<!-- End of deleted X_test.shape cell, input and output -->

<!-- Beginning of newly added business comment to the ends of the 2nd NN Model -->
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">So with this 2nd NN model, we're getting a 96.9% accuracy and losing around 65,460 dollars because of it. Imroved from the first model but we'll tweak it once more.<a class="anchor-link" href="#So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">¶</a></h3>
</div>
</div>
</div>
</div>
<!-- End of newly added business comment to the ends of the 2nd NN Model -->
<!-- I'm at Do another update of the settings -->
</div>
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h2 id="Do-another-update-of-the-settings">Do another update of the settings<a class="anchor-link" href="#Do-another-update-of-the-settings">¶</a></h2>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">model3</span> <span class="o">=</span> <span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Sequential</span><span class="p">()</span>
<span class="n">model3</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">Input</span><span class="p">(</span><span class="n">shape</span> <span class="o">=</span> <span class="p">(</span><span class="mi">67</span><span class="p">,)))</span>
<span class="n">model3</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">30</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'tanh'</span><span class="p">))</span>
<span class="n">model3</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">50</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model3</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">25</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'relu'</span><span class="p">))</span>
<span class="n">model3</span><span class="o">.</span><span class="n">add</span><span class="p">(</span><span class="n">tf</span><span class="o">.</span><span class="n">keras</span><span class="o">.</span><span class="n">layers</span><span class="o">.</span><span class="n">Dense</span><span class="p">(</span><span class="mi">1</span><span class="p">,</span> <span class="n">activation</span> <span class="o">=</span> <span class="s1">'sigmoid'</span><span class="p">))</span>
<span class="n">model3</span><span class="o">.</span><span class="n">compile</span><span class="p">(</span><span class="n">optimizer</span> <span class="o">=</span> <span class="s1">'adam'</span><span class="p">,</span>
              <span class="n">loss</span> <span class="o">=</span> <span class="s1">'binary_crossentropy'</span><span class="p">,</span>
              <span class="n">metrics</span> <span class="o">=</span> <span class="p">[</span><span class="s1">'FalsePositives'</span><span class="p">])</span>
<span class="n">model3</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">X_train</span><span class="p">,</span> <span class="n">y_train</span><span class="p">,</span> <span class="n">epochs</span> <span class="o">=</span> <span class="mi">80</span><span class="p">,</span><span class="n">batch_size</span> <span class="o">=</span> <span class="mi">50</span><span class="p">,</span> <span class="n">validation_data</span><span class="o">=</span> <span class="p">(</span><span class="n">X_test</span><span class="p">,</span> <span class="n">y_test</span><span class="p">))</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of deleted output from the 3rd model's model3.fit(X_train, y_train, epochs = 80,batch_size = 50, validation_data= (X_test, y_test)) -->


<!-- End of deleted output from the 3rd model's model3.fit(X_train, y_train, epochs = 80,batch_size = 50, validation_data= (X_test, y_test)) -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">preds3</span> <span class="o">=</span> <span class="n">model3</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">X_test</span><span class="p">)</span>
<span class="n">make_class3</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">preds3</span><span class="p">:</span>
  <span class="k">if</span> <span class="n">i</span> <span class="o">&gt;</span> <span class="mf">.5</span><span class="p">:</span>
    <span class="n">make_class3</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">1</span><span class="p">)</span>
  <span class="k">else</span><span class="p">:</span>
    <span class="n">make_class3</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="mi">0</span><span class="p">)</span>
</pre></div>
</div>
</div>
</div>
</div>
<!-- Beginning of deleted preds3 = model3.predict(X_test) -->

<!-- End of deleted preds3 = model3.predict(X_test) -->

</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span>
<span class="kn">from</span> <span class="nn">sklearn.metrics</span> <span class="kn">import</span> <span class="n">confusion_matrix</span><span class="p">,</span> <span class="n">ConfusionMatrixDisplay</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="n">cm</span> <span class="o">=</span> <span class="n">confusion_matrix</span><span class="p">(</span><span class="n">make_class3</span><span class="p">,</span> <span class="n">y_test</span><span class="p">)</span>
<span class="n">disp</span> <span class="o">=</span> <span class="n">ConfusionMatrixDisplay</span><span class="p">(</span><span class="n">confusion_matrix</span><span class="o">=</span><span class="n">cm</span><span class="p">)</span>
<span class="n">disp</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child">
<div class="jp-OutputPrompt jp-OutputArea-prompt"></div>
<div class="jp-RenderedImage jp-OutputArea-output" tabindex="0">
<img alt="No description has been provided for this image" class="" src="data:image/png;base64,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ixUGIiJSBPmTHjkkQURE1OiVz2Go/rCCnHMbAw5JEBERkVmsMBARkSIYYQMDn5KoNiYMRESkCJzDIA8TBiIiUgQjbLgOgwycw0BERERmscJARESKYBAFGGS8olrOuY0BEwYiIlIEg8xJjwYOSRARERHdGysMRESkCEbRBkYZT0kY+ZQEERFR48chCXk4JEFERERmscJARESKYIS8Jx2M1gulQWLCQEREiiB/4SZlF+WVffdERERUJawwEBGRIsh/l4Syf8dmwkBERIpghAAj5Mxh4EqPREREjR4rDPIo++6JiIioSlhhICIiRZC/cJOyf8dmwkBERIpgFAUY5azDoPC3VSo7XSIiIqIqYYWBiIgUwShzSELpCzcxYSAiIkWQ/7ZKZScMyr57IiIiqhJWGIiISBEMEGCQsfiSnHMbAyYMRESkCBySkEfZd09ERERVwgoDEREpggHyhhUM1gulQWLCQEREisAhCXmYMBARkSLw5VPyKPvuiYiIasiBAwfQv39/aLVaCIKA+Ph4k+PPPvssBEEw2fr06WPSJjc3FyNGjIBGo4GLiwuioqKQn59v0ub48ePo3r077O3t4ePjg8WLF1eKZevWrWjfvj3s7e0RFBSEnTt3Wnw/TBiIiEgRRAgwythEC+c/FBQUIDg4GKtXr75rmz59+iA7O1vavvjiC5PjI0aMwKlTp5CQkIDt27fjwIEDGD9+vHRcr9cjPDwcvr6+OHz4MJYsWYKYmBh88MEHUpukpCQMGzYMUVFROHr0KAYNGoRBgwbh5MmTFt0PhySIiEgRantIom/fvujbt+8926jVanh5ed3x2JkzZ7Br1y7873//w4MPPggAePfdd/HEE0/g7bffhlarxYYNG1BSUoL169dDpVLhgQceQGpqKpYtWyYlFitWrECfPn0wffp0AMCiRYuQkJCAVatWYe3atVW+H1YYiIiILKDX60224uLiave1b98+eHh4ICAgAM8//zyuX78uHUtOToaLi4uULABAWFgYbGxs8PPPP0ttevToAZVKJbWJiIhAWloabty4IbUJCwszuW5ERASSk5MtipUJAxERKULF663lbADg4+MDZ2dnaYuNja1WPH369MGnn36KxMREvPXWW9i/fz/69u0Lg6H8AU6dTgcPDw+Tc+zs7ODm5gadTie18fT0NGlT8dlcm4rjVcUhCSIiUgSD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"/>
</div>
</div>
</div>
</div>
</div><div class="jp-Cell jp-CodeCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea">
<div class="jp-InputPrompt jp-InputArea-prompt">In [ ]:</div>
<div class="jp-CodeMirrorEditor jp-Editor jp-InputArea-editor" data-type="inline">
<div class="cm-editor cm-s-jupyter">
<div class="highlight hl-python"><pre><span></span><span class="n">cm</span><span class="p">[</span><span class="mi">0</span><span class="p">,</span><span class="mi">1</span><span class="p">]</span> <span class="o">*</span> <span class="mi">100</span> <span class="o">+</span> <span class="n">cm</span><span class="p">[</span><span class="mi">1</span><span class="p">,</span><span class="mi">0</span><span class="p">]</span> <span class="o">*</span> <span class="mi">40</span> <span class="c1"># Down to 63k, with a Deep Learning Neural Network. Add more nodes to the tanh layer to see what happens</span>
</pre></div>
</div>
</div>
</div>
</div>
<div class="jp-Cell-outputWrapper">
<div class="jp-Collapser jp-OutputCollapser jp-Cell-outputCollapser">
</div>
<div class="jp-OutputArea jp-Cell-outputArea">
<div class="jp-OutputArea-child jp-OutputArea-executeResult">
<div class="jp-OutputPrompt jp-OutputArea-prompt">Out[ ]:</div>
<div class="jp-RenderedText jp-OutputArea-output jp-OutputArea-executeResult" data-mime-type="text/plain" tabindex="0">
<pre>63960</pre>
</div>
</div>
</div>
</div>
<!-- Beginning of newly added business comment to the ends of the 3rd NN Model -->
<div class="jp-Cell jp-MarkdownCell jp-Notebook-cell">
<div class="jp-Cell-inputWrapper" tabindex="0">
<div class="jp-Collapser jp-InputCollapser jp-Cell-inputCollapser">
</div>
<div class="jp-InputArea jp-Cell-inputArea"><div class="jp-InputPrompt jp-InputArea-prompt">
</div><div class="jp-RenderedHTMLCommon jp-RenderedMarkdown jp-MarkdownOutput" data-mime-type="text/markdown">
<h3 id="So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">
So with this other LogisticRegression model, we're getting a 97% accuracy and losing around 63,960 dollars because of it. Slight improvement but might be able to do better<a class="anchor-link" href="#So-with-a-LogisticRegression-model,-we're-getting-70%25-accuracy-and-losing-around-736K-dollars-because-of-it">¶</a></h3>
</div>
</div>
</div>
</div>
<!-- End of newly added business comment to the ends of the 3rd NN Model -->

<!-- Deleting everything after 'Realized that it's reducing the FalsePositives but it thinks that 0 is the positive class. Should do falsenegatives to reduce wrong 1s'-->

</main>
</body>
</html>

<h1> The third neural network performed the best. It had an accuracy of 97% and reduced the total loss to 63,690 dollars which is 10 times lower than our first model's 736,820 dollars. </h1>