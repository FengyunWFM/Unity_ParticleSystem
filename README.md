# Unity_ParticleSystem
How to use the ParticleSystem in Unity.
/*
*主要讲如何做粒子特效，讲图片分割后的每一片会成为粒子飞出来。
*并且做成prefab，可以在某些条件下产生这个特效prefab

*/

//在场景中添加空物体，然后加上ParticleSystem组件，在ParticleSystem添加Texture Sheet Aniamtion。
//导入.png图片，新建材质m_material.
//在ParticleSystem的Render>Material选择m_material（将m_material直接拖向场景中的粒子系统也是同理。）然后让m_maretial指向.png
//在ParticleSystem的Texture Sheet Animation>Tiles切分图片有几部分组成。Frame over Time可以设计每一帧的图片。
