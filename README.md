**CST8919 DevOps - Security And Compliance**

**LAB - 3**

**Cloud Platform Tools Overview and Enforcing Organizational Policies in
the Cloud**

**Name : Nirmal Ghosh**

**Part A: Cloud Platform Tools Overview**

**Introduction**

Cloud computing refers to the delivery of computing services over the
internet. This model is more affordable, scalable and flexible than
traditional on-premises infrastructure. Because cloud computing can
support a variety of workloads and aid in digital transformation. It has
become essential to today\'s technological environments.

The major cloud service providers include:

-   **Microsoft Azure:** Microsoft Azure is Microsoft\'s cloud computing
    platform, providing a wide variety of services you can use without
    purchasing and provisioning your own hardware. Azure enables the
    rapid development of solutions and provides the resources to
    accomplish tasks that may not be feasible in an on-premises
    environment. Azure\'s compute, storage, network, and application
    services allow you to focus on building great solutions without the
    need to worry about how the physical infrastructure is assembled.
    (Shahn,2015)

    **Amazon AWS:** AWS provides a highly reliable, scalable, low-cost
    infrastructure platform in the cloud that powers hundreds of
    thousands of businesses in 190 countries around the world.With the
    AWS cloud, not only are infrastructure headaches removed, but so are
    many of the security issues that come with them. AWS's world-class,
    highly secure data centres utilize state-of-the art electronic
    surveillance and multi-factor access control systems.(Sajee,2014)

    **Google Cloud Platform:** Google Cloud Platform offers a wide range
    of services for securing, storing, serving, and analyzing data.
    These cloud services form a secure cloud perimeter for data, where
    different operations and transformations can be carried out on the
    data without it ever leaving the cloud ecosystem. (Ekba,2019)

**Deep Dive into Cloud Tools (Taking Microsoft Azure as an example)**

1.  **Azure Virtual Machines (VMs)**: Azure VMs enable you to deploy and
    manage virtualized Windows and Linux machines in the cloud. There
    are numerous VM sizes and varieties available that are tailored for
    various workloads. Azure virtual machines are frequently used for
    website hosting, application execution, and development and testing.
    (Microsoft documentation)

2.  **Azure Blob Storage**: Azure Blob Storage is a scalable object
    storage service designed to store large amounts of unstructured data
    such as text or binary data. It can be used to store logs, pictures,
    videos, backups, and files.(Microsoft documentation)

1.  **Azure Active Directory**: Azure AD is a cloud-based identity and
    access management solution that offers services for thousands of
    SaaS apps and Azure resources in addition to authentication and
    authorization. To protect user identities and resource access, Azure
    AD offers single sign-on and multi-factor authentication. It also
    supports role-based access control, and identity protection features
    etc...(Microsoft documentation)


1.  **Azure DevOps**: It is a set of cloud based collaboration tools for
    software development including features like version control,
    continuous integration and continuous delivery.With this teams can
    build and deploy applications on to the cloud more effectively and
    much faster than traditional deployment methods.(Microsoft
    documentation)

**Case Study: Telstra Enhances Customer Service with Azure-Based
Generative AI Tools**

Telstra, a company dedicated to innovation and customer-centricity,
sought to equip its front-line employees and customer support
representatives with cutting-edge generative AI tools so they could
handle customer inquiries more quickly and effectively.

**Challenge**

Customer service representatives at Telstra had to search through a
large body of knowledge for solutions which took time and could have led
to inconsistent support. The organization aimed to optimize this
procedure by utilizing generative AI to offer tailored support and
enhance the velocity and precision of client communications.

**Solution**

Based on Microsoft Azure OpenAI Service, Telstra created two state of
the art generative AI tools: Ask Telstra and One Sentence Summary. These
tools were made to easily integrate with Telstra\'s current
infrastructure and give customer support representatives quick access to
pertinent data.

-   **Ask Telstra** : This tool harnesses the power of Azure OpenAI
    Service and Azure AI Search to deliver fast and accurate search
    results from Telstra\'s internal knowledge base. Customer service
    agents can quickly retrieve information to address customer
    inquiries, reducing reliance on manual searches and improving
    response times.

    **One Sentence Summary:** One Sentence Summary is a tool that helps
    Telstra\'s customer service agents quickly understand what a
    customer needs. By clicking a button in Telstra\'s computer system,
    agents can see a short summary of the customer\'s recent history.
    This makes it easier for agents to help customers without needing to
    ask lots of questions or contact them again later.

**Results**

-   **Saving time**: 9 out of 10 agents using One Sentence Summary found
    > they spent less time on calls, and 2 out of 10 calls needed less
    > checking afterward.

    > **Doing better**: More than 8 out of 10 agents using Ask Telstra
    > said it helped them talk to customers in a good way.

    > **Making customers happier**: Agents liked how the tools helped
    > them understand and talk to customers better.

**Part B: Enforcing Organizational Policies in the Cloud**

Azure Policy aids in the large-scale compliance assessment and
enforcement of organizational standards. It offers an aggregated
perspective to assess the general condition of the environment through
its compliance dashboard, with the option to delve down to the
per-resource, per-policy granularity. Bulk remediation for
already-existing resources and automatic remediation for newly-created
resources both aid in bringing your resources into compliance.

Common Policy types include:

**Security Policies:** Cloud security posture can be strengthened with
the help of security standards and recommendations found in Microsoft
Defender for Cloud security policies. Security standards specify
guidelines, requirements for following them, and what should happen
(what happens when conditions aren\'t met). Defender for Cloud evaluates
workloads and resources in relation to the security policies that are
activated in your Google Cloud Platform (GCP) projects, Amazon Web
Services (AWS) accounts, and Azure subscriptions. Security
recommendations give you doable actions to help you address security
vulnerabilities based on those assessments. (Dcurwin,2023)

**Compliance Policies:** Makes sure that cloud operations adhere to
industry rules, including internal governance standards, GDPR, HIPAA,
and PCI DSS. (Dcurwin,2023)

**Resource Utilization policies:** Using auto-scaling rules, instance
scheduling, and resource tagging guidelines, optimize the use of cloud
resources to reduce expenses, enhance performance, and preserve
scalability. (Dcurwin,2023)

**Tools for Policy Enforcement**

**AWS Identity and Access Management (IAM):** It allows organizations to
manage user access to AWS services and resources securely. Policies that
specify permissions based on roles, groups, and users can be created
with the help of IAM.

**Azure Policy:** To guarantee adherence to legal and organizational
requirements, Azure Policy enables enterprises to establish, designate,
and enforce policies across Azure resources. Azure Policy enables the
establishment of guidelines and limitations for tagging conventions,
access controls, and resource configurations.

**Implementing Policies in Practice**

Scenario: An organization needs to enforce specific policies related to
security and compliance in the cloud.

**Step-by-step procedure:**

1.  **Define System Requirements**: Define security and compliance
    requirements based on industry regulations and operational
    requirements.

2.  **Create IAM policies**: Define IAM policies to restrict access to
    critical resources, enforce multi-factor authentication, and
    implement least privilege principles.

3.  **Use Azure Policy**: Configure Azure policy definitions to enforce
    compliance rules such as requiring encryption for storage accounts,
    enforcing network security rules, and enforcing tagging standards

4.  **Use resource tags**: Use resource tags to allocate and track cloud
    resources for cost allocation and resource management purposes.

5.  **Policy implementation**: Provide IAM policy and Azure
    configuration guidelines to users, groups, and related resources to
    set compliance and security standards.

6.  **Monitor and Audit**: Regularly monitor and review policy
    compliance through monitoring logs and compliance reports provided
    by the cloud platform.

**Challenges and Solutions**

**Challenges:**

1.  **Complexity**: Managing policies across multiple cloud environments
    can be complex and challenging to ensure consistency.

2.  **Policy Conflict**: Conflicting policies or overlapping permissions
    may arise leading to confusion and potential security issues.

3.  **Policy Enforcement**: Ensuring consistent enforcement of policies
    across distributed and dynamic cloud environments can be difficult.

**Solutions:**

1.  **Centralized Policy Management**: Use centralized policy management
    tools to define and enforce policies across multiple cloud
    environments from a single interface.

2.  **Policy Testing and Simulation**: Test and simulate policy changes
    before implementation to identify conflicts or unexpected results.

3.  **Continuous Compliance Monitoring**: Implement continuous
    monitoring and automated compliance checks to detect and solve
    policy violations in real-time.

4.  **Regular Policy Review**: Conduct regular reviews of policies to
    ensure they remain aligned with changing business requirements and
    best practices.

**Conclusion**

In conclusion cloud systems like Microsoft Azure offer powerful tools
for agencies allowing scalability and good performance. By using these
equipment efficiently and implementing policies organizations can
improve customer service and meet compliance requirements. Despite the
obvious challenges consisting of complexity and policy conflicts,
centralized control and continuous tracking can help solve them.
Overall, cloud technology helps organizations to innovate and improve in
today\'s virtual landscape.

**References**

1.  Bisong, E. (2019, September 1). *An overview of Google Cloud
    > Platform Services*. SpringerLink.
    > https://link.springer.com/chapter/10.1007/978-1-4842-4470-8_2

2.  Dcurwin. (2023, December). *Security policies in Microsoft Defender
    > for Cloud - Microsoft Defender for Cloud*. Security policies in
    > Microsoft Defender for Cloud - Microsoft Defender for Cloud \|
    > Microsoft Learn.
    > https://learn.microsoft.com/en-us/azure/defender-for-cloud/security-policy-concept

3.  Lakhotia, R. (n.d.). *Telstra dials in elevated customer service
    > with Azure Openai Service*. Microsoft Customers Stories.
    > https://customers.microsoft.com/en-ca/story/1740058425924206437-telstra-telecommunications-azure-openai-service

4.  Mathew, S. (2014, November). *Overview of amazon web services -
    > sysfore*. Overview of Amazon Web Services.
    > https://www.sysfore.com/Assets/PDF/aws-overview.pdf

5.  Shahan, R., & Collier, M. (n.d.). *Microsoft Azure Essentials -
    > Fundamentals of Azure*. Google Books.
    > https://books.google.ca/books?hl=en&lr=&id=EfFxBgAAQBAJ&oi=fnd&pg=PA3&dq=azure%2Bmicrosoft&ots=1wJR5ZNZ35&sig=rjPoKObJ_JFMoN-Em1YqWwTcpAA#v=onepage&q=azure%20microsoft&f=true
