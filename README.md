READ ME
=======

Problem Statement: You are given a dataset containg different parameters that are associated with a particular meter of a customer, we need to build a ML model which helps in predicting the Lossy meter.

Data Description :

client_id : ID of client
Totalizer : Tells about transformer loss
Client count: Tells about number of meters client contains
Capacidad: Capacity of transformer
irr_* : irregular codes count
obs_* : observation codes count
Lossy : Target column

 
lossy irr codes: These irr codes indicates lossy meters

'irr_10', 'irr_12', 'irr_41', 'irr_69', 'irr_95', 'irr_118', 'irr_141', 'irr_163', 'irr_172', 'irr_180', 'irr_185', 'irr_190', 'irr_194', 'irr_198', 'irr_202', 'irr_206', 'irr_209', 'irr_14', 'irr_43', 'irr_71', 'irr_97', 'irr_120', 'irr_143', 'irr_165', 'irr_174', 'irr_181', 'irr_186', 'irr_191', 'irr_195', 'irr_199', 'irr_203', 'irr_207', 'irr_210', 'irr_213', 'irr_215', 'irr_16', 'irr_45', 'irr_22', 'irr_51', 'irr_79', 'irr_104', 'irr_127', 'irr_149', 'irr_166', 'irr_175', 'irr_24', 'irr_53', 'irr_81', 'irr_106', 'irr_151', 'irr_167', 'irr_176', 'irr_182', 'irr_187', 'irr_192', 'irr_196', 'irr_200', 'irr_204', 'irr_208', 'irr_30', 'irr_32', 'irr_60', 'irr_88', 'irr_2', 'irr_62', 'irr_3', 'irr_35', 'irr_63', 'irr_4', 'irr_36', 'irr_64', 'irr_90', 'irr_113', 'irr_136', 'irr_158', 'irr_168', 'irr_177', 'irr_5', 'irr_37', 'irr_159', 'irr_169', 'irr_6', 'irr_38', 'irr_66', 'irr_92', 'irr_115', 'irr_138', 'irr_170', 'irr_178', 'irr_183', 'irr_188', 'irr_193', 'irr_197', 'irr_201', 'irr_205', 'irr_7', 'irr_8', 'irr_179'


lossy_obs_codes : These obs codes indicates lossy meters

'obs_E', 'obs_+', 'obs_Y', 'obs_H', 'obs_Q', 'obs_L', 'obs_O', 'obs_M', 'obs_J', 'obs_A', 'obs_K', 'obs_D', 'obs_W', 'obs_3', 'obs_N', 'obs_4', 'obs_6', 'obs_Z', 'obs_B', 'obs_P', 'obs_I', 'obs_R', 'obs_U', 'obs_2', 'obs_X', 'obs_S', 'obs_T', 'obs_1', 'obs_9', 'obs_V', 'obs_=', 'obs_7', 'obs_-', 'obs_8', 'obs_99'

What to do?

 - You need to build model which helps to predict lossy meters.
 - Predict for test data and create a submissions csv file with row_id,predicted class.
 - Submit code along with submission csv file in a zip file.
