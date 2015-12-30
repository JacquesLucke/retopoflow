CG Cookie RetopoFlow
==========

RetopoFlow is a suite of retopology tools for Blender built by [CG Cookie](http://cgcookie.com). The tools are offered as add-on for Blender that provides a dedicated set of mesh tools designed specifically for retopology, creating a complete workflow in Blender without the need for outside applications.

RetopoFlow includes several tools, all of which automatically snap the resulting mesh to the target object surface. All mesh generation is quad-based and tools are modal. 

# Purchasing and Getting Support
You may purchase RetopoFlow on the [Blender Market](https://cgcookiemarkets.com/all-products/retopoflow/)

Purchasing a license entitles you to tool support and helps ensure RetopoFlows continued development.

## Contours ![Contours Icon](/icons/contours_32.png)
The Contours tool gives you a quick and easy way to retopologize cylindrical forms. Use cases include organic forms, such as arms, legs, tentacles, tails, horns, etc.

The tool works by drawing strokes perpendicular to the form to define the contour of the shape. Immediately upon drawing the first stroke, a preview mesh is generated, showing you exactly what you’ll get. You can draw as many strokes as you like, in any order, from any direction.

### Contours Features
 - Stroke-based contour drawing
 - Easily adjust segments per contour segment
 - Guide Mode: quickly generate whole sections of contour cuts in a single stroke

## Polystrips ![Polystrips Icon](/icons/polystrips_32.png)
The Polystrips tool provides quick and easy ways create the key face loops needed to retopologize a complex model. Use cases include complex forms, such as human faces, creatures, and other organic & hard-surface objects.

The tool works by hand-drawing strokes on to the high-resolution object. The strokes are instantly converted into spline-based strips of polygons, which can be used to quickly map out the key topology flow. Clean mesh previews are generated on the fly, showing you the exact mesh that’ll be created.

### Polystrips Features:
 - Spline-based polygon strip drawing
   - Strip manipulation with bezier spline handles
   - Easily adjust segments per strip
 - 3, 4, and 5-sided patch creation from connected polystrips
   - Automatic segment updating with corresponding polystrips

## Tweak ![Tweak Icon](/icons/tweak_32.png)
The Tweak tool enables easy, brush-based geometry tweaking; enabling the artist to manipulate vertices of a mesh with an adjustable brush (much like sculpting). This yields very fast, and intutitive mesh adjustments that don't require any selection.

## Loop Cut ![Loop Cut Icon](/icons/loop_cut_32.png)
The Loop Cut tool acts like Blender's default Loop Cut and Slide, except that it allows multiple cut within a single modal session and all added loops are automatically snapped to the Source Object's surface.

## Loop Slide ![Loop Slide Icon](/icons/edge_slide_32.png)
As with the Loop Cut tool, the Loop Slide is surface aware, enabling the artist to slide loops along a surface, while staying snapped. In particular this enables sliding of edgeloops that're opposite the current view, while still snapping.

# Getting Support
You can get support for tools by reading the [documentation](http://cgcookiemarkets.com/blender/all-products/retopoflow/?view=docs) or posting on the [forums](http://cgcookiemarkets.com/blender/all-products/retopoflow/?view=support).

# Contributing
Pull requests are welcome! If you'd like to contribute to the project then simply Fork the repo, work on your changes, and then submit a pull request. We are quite strict on what we allow in, but all suggestions are welcome. If you're unsure what to contribute, then look at the [open issues](https://github.com/CGCookie/retopoflow/issues) for the current to-dos.
