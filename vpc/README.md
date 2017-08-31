Infa
======

<table width="100%">
    <tr>
        <th align="left" colspan="2"><h4><a href="https://github.com/petersonwsantos/cloudformation-templates/blob/master/vpc/vpc.yml">VPC (Virtual Private Cloud)</a></h4></th>
    </tr>
    <tr>
        <td width="100%" valign="top">
           <p>Creates an entire VPC from scratch for Lab or Permanent.</p>
           <h6>Create Details</h6>
           <ol>
            <li>Single VPC</li>
            <li> two Public Subnets</li>
            <li> two Private Subnets</li>
            <li>Public Route Table</li>
            <li>Private Route Table</li>
            <li>Internet Gateway</li>
            <ul>
              <li>Attached to the Public Route Table</li>
            </ul>
            <li>VPC Endpoint</li>
            <li>Instance Access Security Group</li>
            <ul>
              <li>Instance to Instance Access</li>
            </ul>
                <li>Remote Access Security Group</li>
           </ol>
        </td>
        <td nowrap width="200" valign="top">
            <table>
                <tr>
                    <th align="left">Launch</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?&templateURL=https://s3.us-east-2.amazonaws.com/petersonwsantos/cloudformation/vpc/vpc.yml" target="_blank"><img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png"></a>
                        <p>us-east-1</p>
                    </td>
                </tr>
            </table>
            <table>
                <tr>
                    <th align="left">View in Designer</th>
                </tr>
                <tr>
                    <td>
                        <a href="https://console.aws.amazon.com/cloudformation/designer/home?region=us-west-2&templateURL=https://s3.us-east-2.amazonaws.com/petersonwsantos/cloudformation/vpc/vpc.yml" target="_blank"><img src="https://s3.us-east-2.amazonaws.com/petersonwsantos/cloudformation/vpc/vpc-designer.png" width:100% alt="View in Designer"></a>
                    </td>
                </tr>
            </table>

</table>

<table>
