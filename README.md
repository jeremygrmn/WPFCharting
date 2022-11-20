# Concept
This project is intended to be a person learning experience. I am making it public so that others can learn and contribute as well.

This is based on the following article: https://www.codeproject.com/Articles/1035375/How-to-Create-a-MVVM-Compatible-Line-Chart-Control

I want to create custom controls that are rooted in the WPF panel coordinate systems

## General control structure
At its basis, there are going to be two main categories of entities per control:
- Control & Code behind
- Engine

The _engine_ is a term I am making in lieu of the above article's "style". Because this class will handle the layout an and logic of the rendered components, I think it is more apt to call this a layout engine
