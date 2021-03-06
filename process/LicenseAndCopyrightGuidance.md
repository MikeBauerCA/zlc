# Considerations for Coding contributions to Zowe

When contributing source code to Zowe, there are two primary requirements that relate to license and copyright notices.

First, all repositories need to contain a license file.  Zowe uses the [Eclipse Public License 2.0 (EPL-2.0)](https://www.eclipse.org/legal/epl-v20.html).  Include the plain-text version of the license, available at https://www.eclipse.org/org/documents/epl-2.0/EPL-2.0.txt, as a LICENSE file in the top-level directory of the Zowe repostiory.

Second, all source files need to include a header to clearly show the license.  They are broken down by donating company for convenience.  `year 1, year 2, ...` describes the relevant copyright years and needs to be decided by the contributing company.  General guidance is `year 1` is the year of first external delivery of the module in object code or source form, the Program or the documentation.  `year 2` is the year of the latest version.

For propertiy or configuration files that do not support comments, the license may be omitted.  If comments are supported the license header should be included.

This is still in draft form.

# CA - Approved for CA Contributions 2018/08/09
````
/**
  This program and the accompanying materials are made available under the terms of the 
  Eclipse Public License v2.0 which accompanies this distribution, and is available at
  https://www.eclipse.org/legal/epl-v20.html

  SPDX-License-Identifier: EPL-2.0

  Copyright Contributors to the Zowe Project.
**/
````

# IBM - Approved for IBM Contributions 2018/08/09
````
/**
  This program and the accompanying materials are made available under the terms of the 
  Eclipse Public License v2.0 which accompanies this distribution, and is available at
  https://www.eclipse.org/legal/epl-v20.html

  SPDX-License-Identifier: EPL-2.0

  Copyright IBM Corporation year 1, year 2
**/
````

# Rocket Software - Approved for Rocket Contributions 2018-08-09
````
/**
  This program and the accompanying materials are made available under the terms of the
  Eclipse Public License v2.0 which accompanies this distribution, and is available at
  https://www.eclipse.org/legal/epl-v20.html

  SPDX-License-Identifier: EPL-2.0
 
  Copyright Contributors to the Zowe Project.
**/
````

This template include both the EPL-2.0 license notice, and a general copyright notice as shown above.

Contributors may choose to include a copyright statement specifying themselves and/or their employer (as applicable) as the copyright holder of their contributions, but the Zowe project does not require this.

Finally, please note that pre-existing third-party license notices and copyright notices *should not be modified or removed* by anyone other than the copyright holder. Please contact the project if you are seeking to contribute code from a third party that is under a license different from EPL-2.0.
