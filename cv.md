#### Curriculum Vitae <h4>
 # Askarov Abdullokh
![user-image](https://media-exp1.licdn.com/dms/image/C5603AQE-K6GAwMOiwg/profile-displayphoto-shrink_400_400/0/1566232551380?e=1632960000&v=beta&t=eNbc8foSikkiAxZuvX-WH7BqzKUQ-pYqS8V_7W1dJOo) <br/> 
e-mail: askarovabulloh111@gmail.com <br/> 
linkedin: [abdullokh-askarov](https://www.linkedin.com/in/abdullokh-askarov/)
 
 Fast links:
 
 [About me](#about-me) <br/>
 [Skills](#skills) <br/>
 [Code examples](#code-examples) <br/>
 [Work experience](#work-experience) <br/>
 [Education](#education) <br/>
 [Volunteer experience](#volunteer-experience) <br/>
 [Languages](#languages) <br/>
 
 <br/>
 
## About me
Hi! I am graduate software engineering student with 4 years of experience in Computer Graphics. <br/>
So far, I worked as:
 1. *UI/UX Designer*, 
 1. *Graphics Designer*, 
 1. *Motion Graphics Designer*, 
 1. *3D generalist*, 
 1. *Unity developer*.
 
A wide range of skills helps me to understand and learn new concepts fast. <br/>
I enjoy working in cross domains and be able to solve challenging tasks. <br/>
Recently, I started working on WebGL and graphics optimization for web. <br/>

<br/>
<br/>
<br/>
 
## Skills
#### Programming languages:
  1. Javascript
  1. Python
 
#### Frameworks:
   1. ReactJS

#### Tools:
  1. Blender, Blender Python development
  1. 3ds Max
  1. Figma,  Adobe XD
  1. Adobe After Effects
 
#### Methodologies:
  1. Agile
 
 <br/>
 <br/>
 <br/>

## Code examples
 Blender custom add-on example:
 ```python
import bpy

bl_info = {
    "name": "Object Selector",
    "blender": (2, 80, 0),
    "category": "Object",
    "author": "Rawdreen"
}


class Operator1(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator1"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.transform.translate(value=(1, 0, 0), orient_type='GLOBAL')
        return {'FINISHED'}


class Operator2(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator2"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.transform.translate(value=(-1, 0, 0), orient_type='GLOBAL')
        return {'FINISHED'}


class Operator3(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator3"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.transform.translate(value=(0, 0, 1), orient_type='GLOBAL')
        return {'FINISHED'}


class Operator4(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator4"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.transform.translate(value=(0, 0, -1), orient_type='GLOBAL')
        return {'FINISHED'}


class Operator5(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator5"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.object.location_clear(clear_delta=False)
        return {'FINISHED'}


class Operator6(bpy.types.Operator):
    """Tooltip"""
    bl_idname = "object.operator6"
    bl_label = "Simple Object Operator"

    def execute(self, context):
        bpy.ops.transform.resize(value=(3.12037, 3.12037, 3.12037), orient_type='GLOBAL', orient_matrix=(
            (1, 0, 0), (0, 1, 0), (0, 0, 1)), orient_matrix_type='GLOBAL')
        return {'FINISHED'}


class ObjectSelector_PT_panel(bpy.types.Panel):
    bl_label = "Select object"
    bl_idname = "objectSelector"
    bl_space_type = "VIEW_3D"
    bl_region_type = "UI"
    bl_category = "Object Selector"

    def draw(self, context):
        layout = self.layout
        layout.label(text="Object Selector")

        layout.use_property_split = True
        layout.use_property_decorate = True

        self.layout.label(text="Values")
        row = layout.row(align=True)
        subrow1 = row.row(align=True)
        subrow1.operator(Operator1.bl_idname, text="", icon="TRIA_LEFT")
        subrow1 = row.row(align=True)
        subrow1.operator(Operator2.bl_idname, text="", icon="TRIA_RIGHT")
        subrow1 = row.row(align=True)
        subrow1.operator(Operator3.bl_idname, text="", icon="TRIA_UP")
        subrow1 = row.row(align=True)
        subrow1.operator(Operator4.bl_idname, text="", icon="TRIA_DOWN")
        row.split()

        self.layout.label(text="Values 2")
        row = row.row()
        row.operator(Operator5.bl_idname, text="RESET",
                     icon="FULLSCREEN_EXIT")

        # col = layout.row(align=True)
        # col.operator(Operator5.bl_idname, text="RESET", icon="FULLSCREEN_EXIT")


_classes = [
    ObjectSelector_PT_panel,
    Operator1,
    Operator2,
    Operator3,
    Operator4,
    Operator5
]


def register():
    for cls in _classes:
        bpy.utils.register_class(cls)


def unregister():
    for cls in _classes:
        bpy.utils.unregister_class(cls)


if __name__ == "__main__":
    register()
```

<br/>
<br/>
<br/>


## Work experience
 #### graphics designer / software developer (2019 - present)
 ###### Raisense
Raisense is a fast-growing IT company in Uzbekistan. Here, we work closely with android, iOS, front-end, and back-end developers, so each of us understands the process and limitation of technologies we use. It helps us to understand each other and deliver IT-solutions faster. <br/>

As a graphics designer/software developer at Raisense, my tasks include (but not limited to):
1. Delivery of UI/UX design for mobile and web applications;
1. Motion graphics for promoting our products and services;
1. 3D visualization;
1. Script development for workflow optimization in Adobe environment;
1. XR app development for industries;

Tools I frequently use:
1. 2D Graphics: Adobe XD, Figma, Adobe Illustrator, Adobe After Effects;
1. 3D Graphics: Autodesk AutoCAD, Autodesk 3ds Max, Blender;
1. Programming languages: C#, Javascript;
 
<br/>
<br/>
<br/>

 
## Education
 1. #### TUIT - Master's degree in Computer vision and AI (2020-2022)<br/>
    *Synthetic dataset generation for ML using 3d modeling software*
 1. #### INHA - Bachelor's degree in Computer Science and Engineering (2016-2020)
 
 <br/>
 <br/>
 <br/>

## Volunteer experience
#### Lead Organizer (2020)
###### Microsoft Learn Student Ambassadors 
 Being Microsoft Student Partner:
1. Organized Microsoft Minecraft coding event for more than 200 school kids at the leading IT school named after al-Khwarizmi at Tashkent with help of 20 and more volunteers including Microsoft Student Partner, students of Inha University in Tashkent, team Raisense and school representatives.
1. Mentored a team of 15 amazing students on algorithm and code structuring.
1. Developed a unique themed design for the event.
1. With the help of representatives of the school made mass media coverage to popularize IT-sphere at Uzbekistan.

[watch event report on youtube](https://www.youtube.com/watch?v=6c5AZzlaII4&list=PL2R6crW6nuP1k-Mf-8ete8yTvuwMaBUdP)
 
<br/>
<br/>
<br/>

 ## Languages
  * English - Full professional proficiency
  * Italian - Limited working proficiency
  * Korean - Elementary proficiency
  * Russian - Native or bilingual proficiency
  * Uzbek - Native or bilingual proficiency
 
 
 
