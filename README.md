# RectangularGradientDrawable

It creates a rectangle gradient shape of many colours from the centre to the exterior

It can be set as background of a view to be the shadow

![RectangularGradientDrawable](https://cloud.githubusercontent.com/assets/6752432/8513409/9bebd6f0-236a-11e5-8931-6a9f8e47ef0e.jpg)
-------
### Usage

###### 2 colors

    Drawable rectDrawable = new RectangularGradientDrawable( Color.RED, Color.BLUE );
    myView.setBackground(rectDrawable);

###### Multiple colors

    Drawable rectDrawable = new RectangularGradientDrawable( new int[] { Color.GREEN, Color.BLUE, Color.YELLOW, Color.RED }, new float[] { 0f, 0.3f, 0.6f, 1f } );
    myView.setBackground(rectDrawable);
-------
    Copyright 2015 Tiziano Munegato
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
        http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
