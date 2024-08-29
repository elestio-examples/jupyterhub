# JupyterHub CI/CD pipeline

<a href="https://dash.elest.io/deploy?source=cicd&social=dockerCompose&url=https://github.com/elestio-examples/jupyterhub"><img src="deploy-on-elestio.png" alt="Deploy on Elest.io" width="180px" /></a>

Deploy JupyterHub server with CI/CD on Elestio

<img src="jupyterhub.png" style='width: 30%;'/>
<br/>
<br/>

# Once deployed ...

You can open JupyterHub UI here:

    URL: https://[CI_CD_DOMAIN]
    password: [ADMIN_PASSWORD]

Currently, the username `admin` has administrative privileges. To grant additional users the same level of access, go to `./scripts/preInstall.sh` and add the desired users under the following line:

    c.PAMAuthenticator.admin_users = {'admin', ...}

